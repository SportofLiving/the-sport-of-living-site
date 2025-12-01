# The Sport of Living - Static Website

A minimalist, personal website for adults 50+ focused on well-being.

## Project Structure

```
the_sport_of_living/
├── assets/
│   ├── css/
│   │   └── styles.css          # Global stylesheet
│   └── photos/
│       ├── photo-1.jpg         # Carlos in office
│       ├── photo-2.jpg         # Young Carlos competing
│       ├── photo-3.jpg         # Carlos at sports park
│       ├── photo-4.jpg         # Carlos at Cannes
│       ├── photo-5.jpg         # Carlos beside bars
│       ├── photo-6.jpg         # Woman running
│       ├── photo-7.jpg         # Carlos at sports park
│       ├── photo-8.jpg         # Woman preparing food
│       ├── photo-9.jpg         # Carlos at Cannes sunset
│       └── photo-10.jpg        # Carlos vertical portrait
├── index.html                  # Page 1 - Landing page
├── page2.html                  # Page 2 - Email sent / Basic Plan
├── page3.html                  # Page 3 - Payment confirmation
├── page3a.html                 # Page 3a - POP/VIP plan selection
├── page4.html                  # Page 4 - POP welcome
├── page5.html                  # Page 5 - VIP welcome
├── page6.html                  # Page 6 - VIP upgrade
├── privacy-policy.html        # Privacy Policy
├── terms-of-service.html      # Terms of Service
└── Route aliases (symlinks):
    ├── send.html → page2.html
    ├── plan.html → page3.html
    ├── submit.html → page3a.html
    ├── pop.html → page4.html
    ├── premium.html → page5.html
    └── vip.html → page6.html
```

## Routing

### Internal Routes (Abacus)
- `/` → Page 1 (Landing)
- `/page2` → Page 2 (Email Sent)
- `/page3` → Page 3 (Payment Confirmation)
- `/page3a` → Page 3a (Plan Selection)
- `/page4` → Page 4 (POP Welcome)
- `/page5` → Page 5 (VIP Welcome)
- `/page6` → Page 6 (VIP Upgrade)
- `/privacy-policy` → Privacy Policy
- `/terms-of-service` → Terms of Service

### Public Domain Routes (www.thesportofliving.com)
- `/` → Page 1 (Landing)
- `/send` → Page 2 (Form 1 confirmation redirect)
- `/plan` → Page 3 (Basic Plan payment return)
- `/submit` → Page 3a (Form 2 confirmation redirect)
- `/pop` → Page 4 (POP subscription redirect)
- `/premium` → Page 5 (VIP subscription redirect)
- `/vip` → Page 6 (VIP upgrade entry)
- `/privacy-policy` → Privacy Policy
- `/terms-of-service` → Terms of Service

## User Flow

1. **Page 1 (Landing)** → User fills Form 1 → Redirects to `/send`
2. **Page 2 (/send)** → User pays $6.99 via PayPal → Redirects to `/plan`
3. **Page 3 (/plan)** → User fills Form 2 → Redirects to `/submit`
4. **Page 3a (/submit)** → User chooses:
   - POP Plan → Redirects to `/pop` (Page 4)
   - VIP Plan → Redirects to `/premium` (Page 5)
5. **Page 4 (/pop)** → POP welcome + link to `/vip` for upgrade
6. **Page 6 (/vip)** → Upgrade offer → Redirects to `/premium` (Page 5)
7. **Page 5 (/premium)** → VIP welcome (final destination)

## PayPal Integration

### 4 Payment Buttons:
1. **Basic Plan** (Page 2) - One-time $6.99 payment
   - Product ID: NJN6MFQ2BHZMU
   - Return URL: /plan

2. **POP Subscription** (Page 3a) - $12.99/month (after Basic Plan credit)
   - Plan ID: P-74A73468Y0022730JNEHWXIY
   - onApprove redirect: /pop

3. **VIP Subscription** (Page 3a) - $32.99/month (after Basic Plan credit)
   - Plan ID: P-8D491570ED588515TNEHXEBQ
   - onApprove redirect: /premium

4. **POP to VIP Upgrade** (Page 6) - $20/month difference
   - Plan ID: P-4TY11014S4757831NNEMIPEA
   - onApprove redirect: /premium

## Google Forms Integration

### 2 Embedded Forms:
1. **Form 1** (Page 1) - Initial information collection
   - Confirmation redirects to: /send

2. **Form 2** (Page 3) - Detailed questions for optimization
   - Confirmation redirects to: /submit

## Design Specifications

- **Color Palette:**
  - Light gray-violet background (#f0ebf8, #e8e2f3)
  - PayPal blue accents (#0070ba)
  - PayPal gold for VIP elements (#ffc439)

- **Typography:**
  - Font: Helvetica Neue, Arial, sans-serif
  - Body: 18px
  - H1: 32px
  - Subheadlines: 22px

- **Responsive:**
  - Mobile-first design
  - Single column on mobile
  - Multi-column layouts on desktop

## Running Locally

```bash
# Start a simple HTTP server
cd /home/ubuntu/the_sport_of_living
python3 -m http.server 8000

# Access at:
http://localhost:8000/
```

## Key Requirements

- ✅ Pure static HTML/CSS/JS (no frameworks)
- ✅ No authentication or login system
- ✅ Exact text from canonical document
- ✅ Exact PayPal button codes (no modifications)
- ✅ Exact Google Forms iframe codes
- ✅ Medical disclaimer on every page
- ✅ Footer on every page with legal links
- ✅ Responsive design for all devices
- ✅ Light gray-violet backgrounds
- ✅ PayPal blue/gold color accents

## Contact

- Email: sportofliving@gmail.com
- Address: 8721 Santa Monica Boulevard, Los Angeles, CA 90069

© 2025 The Sport of Living by Carlos Martinez. All rights reserved.
