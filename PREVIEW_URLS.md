# The Sport of Living - Preview URLs

## 🌐 Server Status

✅ **Server is RUNNING**  
✅ **Port:** 8000  
✅ **Preview Base URL:** https://104bbd5f62.preview.abacusai.app:8000

---

## 📋 Complete List of Page URLs

### 1. Page 1 - Landing Page
**Description:** Carlos's story with Form 1 (initial information collection)  
- **Direct File URL:** https://104bbd5f62.preview.abacusai.app:8000/index.html  
- **Route Alias:** https://104bbd5f62.preview.abacusai.app:8000/

### 2. Page 2 - Email Sent / Basic Plan
**Description:** Form 1 confirmation + Basic Plan offer ($6.99)  
- **Direct File URL:** https://104bbd5f62.preview.abacusai.app:8000/page2.html  
- **Route Alias:** https://104bbd5f62.preview.abacusai.app:8000/send

### 3. Page 3 - Payment Confirmation
**Description:** Basic Plan payment confirmation + Form 2  
- **Direct File URL:** https://104bbd5f62.preview.abacusai.app:8000/page3.html  
- **Route Alias:** https://104bbd5f62.preview.abacusai.app:8000/plan

### 4. Page 3a - Plan Selection
**Description:** Choose between POP and VIP subscriptions  
- **Direct File URL:** https://104bbd5f62.preview.abacusai.app:8000/page3a.html  
- **Route Alias:** https://104bbd5f62.preview.abacusai.app:8000/submit

### 5. Page 4 - POP Welcome
**Description:** POP subscription welcome page + VIP upgrade option  
- **Direct File URL:** https://104bbd5f62.preview.abacusai.app:8000/page4.html  
- **Route Alias:** https://104bbd5f62.preview.abacusai.app:8000/pop

### 6. Page 5 - VIP Welcome
**Description:** VIP subscription welcome page (final destination)  
- **Direct File URL:** https://104bbd5f62.preview.abacusai.app:8000/page5.html  
- **Route Alias:** https://104bbd5f62.preview.abacusai.app:8000/premium

### 7. Page 6 - VIP Upgrade
**Description:** Upgrade offer from POP to VIP ($20/month)  
- **Direct File URL:** https://104bbd5f62.preview.abacusai.app:8000/page6.html  
- **Route Alias:** https://104bbd5f62.preview.abacusai.app:8000/vip

### 8. Privacy Policy
**Description:** Privacy policy page  
- **Direct File URL:** https://104bbd5f62.preview.abacusai.app:8000/privacy-policy.html

### 9. Terms of Service
**Description:** Terms of service page  
- **Direct File URL:** https://104bbd5f62.preview.abacusai.app:8000/terms-of-service.html

---

## 🚀 Quick Access Links

Use these URLs for quick navigation during testing:

| Page | URL | Purpose |
|------|-----|---------|
| 🏠 **Landing** | https://104bbd5f62.preview.abacusai.app:8000/ | Start here |
| 📧 **Send** | https://104bbd5f62.preview.abacusai.app:8000/send | Form 1 redirect |
| 💳 **Plan** | https://104bbd5f62.preview.abacusai.app:8000/plan | Basic Plan return |
| 📝 **Submit** | https://104bbd5f62.preview.abacusai.app:8000/submit | Form 2 redirect |
| ⭐ **POP** | https://104bbd5f62.preview.abacusai.app:8000/pop | POP subscription |
| 👑 **Premium** | https://104bbd5f62.preview.abacusai.app:8000/premium | VIP subscription |
| 🔝 **VIP** | https://104bbd5f62.preview.abacusai.app:8000/vip | VIP upgrade |

---

## 🔄 User Flow with URLs

```
1. Landing (/)
   https://104bbd5f62.preview.abacusai.app:8000/
   ↓ Fill Form 1
   
2. Email Sent (/send)
   https://104bbd5f62.preview.abacusai.app:8000/send
   ↓ Pay $6.99 Basic Plan
   
3. Payment Confirmation (/plan)
   https://104bbd5f62.preview.abacusai.app:8000/plan
   ↓ Fill Form 2
   
4. Plan Selection (/submit)
   https://104bbd5f62.preview.abacusai.app:8000/submit
   ↓ Choose Plan:
   
   ├─ POP ($12.99/mo)
   │  https://104bbd5f62.preview.abacusai.app:8000/pop
   │  ↓ Optional Upgrade
   │  https://104bbd5f62.preview.abacusai.app:8000/vip
   │  ↓ Pay $20/mo upgrade
   │
   └─ VIP ($32.99/mo)
      https://104bbd5f62.preview.abacusai.app:8000/premium
      ✅ VIP Status
```

---

## 🛠️ Technical Details

### Server Information
- **Process ID:** Running on Python HTTP server
- **Port:** 8000
- **Directory:** /home/ubuntu/the_sport_of_living
- **Protocol:** HTTPS (via Abacus.AI preview proxy)

### Route Configuration
All route aliases are implemented as symbolic links:
- `send.html` → `page2.html`
- `plan.html` → `page3.html`
- `submit.html` → `page3a.html`
- `pop.html` → `page4.html`
- `premium.html` → `page5.html`
- `vip.html` → `page6.html`

### Domain Structure
Both direct file URLs and route aliases work correctly:
- Direct: `/page2.html`
- Alias: `/send` (for user-facing routes)

---

## 📱 Testing Checklist

Use these URLs to test each page:

- [ ] **Landing Page** - https://104bbd5f62.preview.abacusai.app:8000/
- [ ] **Email Sent** - https://104bbd5f62.preview.abacusai.app:8000/send
- [ ] **Payment Confirmation** - https://104bbd5f62.preview.abacusai.app:8000/plan
- [ ] **Plan Selection** - https://104bbd5f62.preview.abacusai.app:8000/submit
- [ ] **POP Welcome** - https://104bbd5f62.preview.abacusai.app:8000/pop
- [ ] **VIP Welcome** - https://104bbd5f62.preview.abacusai.app:8000/premium
- [ ] **VIP Upgrade** - https://104bbd5f62.preview.abacusai.app:8000/vip
- [ ] **Privacy Policy** - https://104bbd5f62.preview.abacusai.app:8000/privacy-policy
- [ ] **Terms of Service** - https://104bbd5f62.preview.abacusai.app:8000/terms-of-service

---

## 📞 Contact Information

**Email:** sportofliving@gmail.com  
**Address:** 8721 Santa Monica Boulevard, Los Angeles, CA 90069

---

**Generated:** November 25, 2025  
**Server Status:** ✅ ACTIVE  
**All Pages:** ✅ ACCESSIBLE
