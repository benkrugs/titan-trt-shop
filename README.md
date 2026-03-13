# Titan TRT Google Shopping Landing Page

**High-converting product page for Google Shopping ads**

---

## 🎯 Purpose

This landing page is optimized for Google Shopping campaigns promoting Titan TRT's injectable testosterone therapy. Designed to match Titan's branding while maximizing conversions.

---

## ✅ Key Features

- **Mobile-First Design:** CTA button above the fold on all devices
- **Titan Branding:** Matches official Titan color scheme and messaging
- **Product-Focused:** Similar layout to Maximus Tribe and TMates product pages
- **Conversion-Optimized:** Multiple CTAs throughout page
- **LegitScript Badge:** Trust signal in footer
- **Affiliate Tracking:** All links include proper tracking parameters

---

## 🔗 Affiliate URL

**All CTAs link to:**
```
https://jointitan.com/?toclid=TO-2RbC8WhCGKBLFQ2J90aUB9&utm_source=theoffer&utm_campaign=94&sub1=shop
```

**Tracking parameters:**
- `toclid`: TheOffer click ID
- `utm_source`: theoffer
- `utm_campaign`: 94
- `sub1`: shop (identifies Google Shopping traffic)

---

## 📄 Page Structure

### Above the Fold (Mobile)
- ✅ Titan logo + header
- ✅ Hero headline ("Premium Injectable Testosterone Therapy")
- ✅ Price box ($99/month)
- ✅ **PRIMARY CTA BUTTON** ("Shop Now - Start for $49")
- ✅ Trust badges (Doctor Prescribed, Free Shipping, Discreet Packaging)

### Product Section
- Product image placeholder (💉 emoji - replace with real image)
- Key features (5 bullet points)
- Drug facts box (dosage, application, concentration)
- Secondary CTA button

### Benefits Grid
- 4 benefit cards (Muscle & Strength, Sexual Performance, Memory & Focus, Energy & Mood)
- Based on clinical research from Maximus page

### How It Works
- 4-step process (Questionnaire → Blood Test → Treatment Plan → Follow-Up)
- Clear, simple timeline

### Footer
- Titan branding
- Navigation links
- **LegitScript badge** (placeholder - needs image upload)
- Medical disclaimer
- Legal copy

---

## 🖼️ Image Requirements

### LegitScript Badge
**File needed:** `legitscript-badge.png`

Upload your LegitScript certification badge image to the same directory as `index.html`.

**Recommended specs:**
- Format: PNG (transparent background)
- Height: 60-80px
- Aspect ratio: Maintain original

**Current placeholder:**
```html
<img src="legitscript-badge.png" alt="LegitScript Certified" style="height: 60px;">
```

### Product Image (Optional Enhancement)
Replace the emoji placeholder (💉) with a professional product image:
- Vial of testosterone
- Syringe with vial
- Packaging shot
- Doctor/clinician image

**To replace:**
1. Upload image file
2. Update line in HTML:
```html
<div class="product-image-placeholder">💉</div>
```
Change to:
```html
<img src="product.jpg" alt="Titan Injectable TRT" style="max-width: 100%;">
```

---

## 🚀 Deployment Options

### Option 1: Netlify (Recommended)
1. Push to GitHub repo
2. Connect to Netlify
3. Auto-deploy from main branch
4. Add custom domain

### Option 2: GitHub Pages
1. Push to GitHub
2. Enable GitHub Pages in repo settings
3. Serve from `main` branch

### Option 3: Simple Hosting
1. Upload `index.html` + `legitscript-badge.png` to any web host
2. Point domain to hosting

---

## 🎨 Design Specifications

**Color Palette (Titan Branding):**
- Primary Blue: `#1E3A8A`
- Dark Blue: `#1E293B`
- Orange (CTA): `#F97316`
- Orange Hover: `#EA580C`

**Typography:**
- System fonts for fast loading
- Sans-serif stack: `-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto`

**Responsive Breakpoints:**
- Mobile: < 768px
- Tablet: 768px - 1023px
- Desktop: ≥ 1024px

---

## 📊 Conversion Elements

### CTA Buttons (6 total)
1. **Header CTA** (desktop only)
2. **Hero CTA** (primary, above fold)
3. **Product Section CTA**
4. **Footer CTA**
5. All footer links
6. Logo link

### Trust Signals
- ✓ Doctor Prescribed
- ✓ Free Shipping
- ✓ Discreet Packaging
- ✓ LegitScript Certification
- ✓ Medical Disclaimer

### Social Proof Elements
- Price transparency ($99/month, start for $49)
- 30-day supply information
- "Fully refundable if not approved" guarantee
- 4-step process clarity

---

## 🔧 Customization

### Change Pricing
Edit the price box in the hero section:
```html
<div class="price">$99<span class="price-small">/month</span></div>
```

### Update Messaging
Main copy sections to customize:
- Hero headline (line 299)
- Hero subtitle (line 300)
- Product description (line 319)
- Benefits cards (lines 400-430)

### Modify CTAs
All CTA buttons use the same structure:
```html
<a href="[AFFILIATE URL]" class="btn btn-large">Button Text</a>
```

---

## 📈 Google Shopping Setup

### Campaign Settings
- **Campaign Type:** Shopping
- **Bidding:** Target ROAS or Manual CPC
- **Product Feed:** Must include Titan TRT product
- **Landing Page:** This page URL

### Product Feed Requirements
```
title: Titan Injectable TRT - Premium Testosterone Therapy
description: Doctor-prescribed testosterone replacement therapy. Free shipping, discreet packaging. Start for $49.
price: 99.00 USD
availability: in stock
brand: Titan
condition: new
```

### Tracking
All links include `sub1=shop` to identify Google Shopping traffic in Titan's analytics.

---

## ⚠️ Compliance Notes

**Medical Disclaimers:**
- ✅ "Not intended to diagnose, treat, cure, or prevent disease" (included)
- ✅ "Results may vary" (included)
- ✅ Prescription requirement implied (included)

**FTC Requirements:**
- Clear pricing ($99/month displayed prominently)
- Refund policy stated
- Product details transparent

**LegitScript:**
- Badge must be current and valid
- Link to LegitScript verification page (optional)

---

## 📝 TODO Before Launch

- [ ] Upload LegitScript badge image (`legitscript-badge.png`)
- [ ] Optional: Replace emoji with real product image
- [ ] Test all CTA links (should go to Titan affiliate URL)
- [ ] Verify mobile display (CTA above fold)
- [ ] Test on multiple devices (iPhone, Android, desktop)
- [ ] Confirm LegitScript badge displays correctly
- [ ] Set up Google Shopping campaign
- [ ] Add Google Analytics tracking (optional)

---

## 🎯 Expected Performance

**Conversion Rate Target:** 3-6%  
**Avg CPC:** $8-15 (TRT niche)  
**Avg Order Value:** $99 (first month)

**Revenue Projection (at 5% CVR):**
- 1,000 clicks = 50 conversions × $99 = $4,950
- Less ad spend ($8 CPC × 1,000 = $8,000)
- Profit/Loss depends on Titan's commission structure

---

## 📧 Support

For questions or modifications, refer to Titan's affiliate manager or contact support.

**Affiliate URL Format:**
```
https://jointitan.com/?toclid=[CLICK_ID]&utm_source=theoffer&utm_campaign=94&sub1=shop
```

---

**Built:** March 2026  
**Version:** 1.0  
**Status:** Ready for deployment (pending LegitScript badge upload)
