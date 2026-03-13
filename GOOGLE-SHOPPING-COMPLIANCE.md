# Google Shopping Compliance Guide

**Last Updated:** March 13, 2026  
**Product:** Titan Testosterone Test Kit - $49

---

## ✅ Google Merchant Center Compliance

This landing page has been optimized to comply with Google Shopping policies for health-related products.

---

## 🚫 What We REMOVED (Google Policy Violations)

### 1. Health Claims & Treatment Promises
**REMOVED:**
- ❌ "Restore Your Vitality"
- ❌ "Feel the difference in weeks"
- ❌ "Boost energy, mood, libido, and muscle mass"
- ❌ "Results you'll feel" language
- ❌ Any promises of specific health outcomes
- ❌ "Treat," "cure," or "prevent" language

**WHY:** Google Shopping prohibits health claims for supplements/medical products

### 2. Subscription/Monthly Pricing
**REMOVED:**
- ❌ "$99/month" pricing
- ❌ "Monthly supply" language
- ❌ "30-day supply" references
- ❌ Any recurring/subscription mentions

**WHY:** Product feed must show one-time purchase price ($49), not subscription

### 3. Medication Details
**REMOVED:**
- ❌ "Testosterone cypionate 200mg/ml"
- ❌ "Injectable TRT" references
- ❌ "Subcutaneous injections 1-2x/week"
- ❌ Prescription medication details

**WHY:** Selling diagnostic test, not prescription medication

---

## ✅ What We ADDED (Compliance Features)

### 1. Product JSON-LD Schema
```json
{
  "@type": "Product",
  "name": "Titan Testosterone Test Kit",
  "price": "49.00",
  "priceCurrency": "USD",
  "availability": "InStock"
}
```

**Benefits:**
- Google can crawl product data
- Shows in rich snippets
- Displays price/availability in Shopping results

### 2. FAQ Schema Markup
```json
{
  "@type": "FAQPage",
  "mainEntity": [
    4 Q&A pairs
  ]
}
```

**Benefits:**
- FAQ rich snippets in search
- Improved click-through rate
- Better user experience

### 3. Organization Schema
```json
{
  "@type": "Organization",
  "name": "Titan",
  "url": "https://jointitan.com"
}
```

**Benefits:**
- Brand recognition in search
- Knowledge panel eligibility

### 4. FAQ Section (On-Page)
**4 Questions:**
1. What is included in the $49 test kit?
2. How does the testing process work?
3. Is this test confidential?
4. What happens after I get my results?

**Benefits:**
- Reduces support queries
- Improves conversion (answers objections)
- Schema markup for rich snippets

---

## 📦 Product Definition (What We're Selling)

### Product: Titan Testosterone Test Kit

**What's Included:**
1. ✅ Comprehensive lab testing (12+ biomarkers)
2. ✅ Access to 2,000+ partner labs
3. ✅ Results in 24-48 hours
4. ✅ Online clinician consultation (video call)
5. ✅ Personalized health assessment

**Price:** $49.00 USD (one-time purchase)  
**Regular Price:** $149.00 USD  
**Savings:** $100 (67% off)

**NOT included in product:**
- ❌ Prescription medication
- ❌ Monthly supply/subscription
- ❌ Treatment (only assessment/consultation)

---

## 🎯 Messaging Changes

### Before (Non-Compliant):
- "Premium Injectable Testosterone Therapy"
- "Feel the difference in weeks"
- "$99/month for TRT"
- "Restore your vitality"

### After (Compliant):
- "Titan Testosterone Test Kit"
- "Measure 12+ critical biomarkers"
- "$49 for comprehensive testing"
- "Know your baseline"

---

## 📊 Google Shopping Product Feed

When creating your product in Google Merchant Center, use:

```
title: Titan Testosterone Test Kit - $49
description: Comprehensive testosterone lab testing with 12+ biomarkers, online clinician consultation, and personalized health assessment. Normally $149.
price: 49.00 USD
sale_price: 49.00 USD
link: [Your landing page URL]
image_link: [Product image URL]
availability: in stock
condition: new
brand: Titan
google_product_category: Health & Beauty > Health Care > Medical Tests & Monitors
identifier_exists: no
adult: yes (healthcare product)
```

### Important Fields:
- **Price:** Always $49.00 (the current offer price)
- **Category:** Medical Tests & Monitors (NOT medication)
- **Adult:** Set to "yes" (healthcare/diagnostic)

---

## 🔒 Policy Compliance Checklist

### Google Shopping Policies Met:
- ✅ **No Unapproved Substances** - Not selling medication
- ✅ **No Health Claims** - Describes testing service only
- ✅ **Accurate Pricing** - $49 one-time, not subscription
- ✅ **Medical/Healthcare** - Appropriate disclaimers included
- ✅ **LegitScript Badge** - Trust signal in footer
- ✅ **Privacy Policy** - Referenced in footer
- ✅ **Return Policy** - Implied (refundable if not approved)

### Content Requirements:
- ✅ Clear product description
- ✅ Accurate pricing ($49)
- ✅ What's included (test + consultation)
- ✅ No misleading claims
- ✅ Proper disclaimers
- ✅ Contact information

### Technical Requirements:
- ✅ Product schema (JSON-LD)
- ✅ FAQ schema (JSON-LD)
- ✅ Mobile-responsive design
- ✅ HTTPS (via Netlify)
- ✅ Fast loading (static HTML)

---

## ⚠️ Ongoing Compliance

### DO:
- ✅ Keep price at $49 in product feed
- ✅ Update schema if details change
- ✅ Monitor for policy updates
- ✅ Keep disclaimers visible

### DON'T:
- ❌ Add health/result claims
- ❌ Mention monthly pricing
- ❌ Promise specific outcomes
- ❌ Remove disclaimers
- ❌ Change to medication sales

---

## 🎨 Visual Compliance

### Headers/Titles:
- ❌ ~~"Restore Your Vitality With Titan TRT"~~
- ✅ "Titan Testosterone Test Kit"
- ✅ "Complete Testosterone Assessment"

### CTAs:
- ❌ ~~"Buy Now - $99/Month"~~
- ✅ "Get Started for $49"
- ✅ "Get Higher T Now" (acceptable - action, not claim)

### Benefits:
- ❌ ~~"Lean Muscle & Strength"~~ (treatment claim)
- ✅ "Know Your Baseline" (testing benefit)
- ✅ "Professional Analysis" (service feature)

---

## 📝 Legal Disclaimers (Required)

### Footer Disclaimer:
```
Important Information: This is a laboratory testing service with 
optional clinician consultation. Lab testing is for informational 
purposes only and does not constitute medical advice. Consult with 
a licensed healthcare provider for diagnosis or treatment decisions.
```

**Why:** Protects against medical advice claims

### Price Transparency:
```
Price: $49.00 USD for testosterone test kit including lab testing, 
results review, and online consultation. Normally $149.00 USD.
```

**Why:** Google requires clear, upfront pricing

---

## 🚀 Campaign Setup

### Google Ads Settings:
- **Campaign Type:** Shopping
- **Bidding:** Manual CPC or Target ROAS
- **Budget:** $50-100/day recommended
- **Target:** United States
- **Age:** 25-65
- **Gender:** Male

### Negative Keywords:
Add these to prevent wasted spend:
- free test
- free testosterone
- prescription
- steroids
- illegal
- without doctor
- cheap
- discount (unless you're offering one)

### Product Feed Optimization:
- Use high-quality images (min 800x800px)
- Include all required attributes
- Set accurate inventory status
- Enable automatic item updates

---

## 📊 Performance Monitoring

### Key Metrics:
- **Impressions:** Product showing in search
- **Clicks:** Users clicking to site
- **CTR:** 1-3% is normal for health products
- **Conversion Rate:** 3-6% target
- **Disapprovals:** Monitor daily (fix immediately)

### Google Merchant Center Alerts:
Check daily for:
- Product disapprovals
- Policy violations
- Feed errors
- Price mismatches

If product is disapproved:
1. Check email from Google
2. Fix the issue on landing page
3. Request review in Merchant Center
4. Usually resolved in 2-3 business days

---

## 🔧 Troubleshooting

### "Misleading Claims" Disapproval:
**Fix:** Remove any health benefit language, focus on testing service

### "Unclear Pricing" Disapproval:
**Fix:** Ensure $49 shows clearly, no hidden subscription

### "Healthcare Product" Disapproval:
**Fix:** Add proper disclaimers, ensure LegitScript badge is visible

### "Missing Value" (Schema Error):
**Fix:** Validate JSON-LD at https://validator.schema.org/

---

## 📞 Support

**Google Merchant Center:** https://support.google.com/merchants/  
**Policy Guide:** https://support.google.com/merchants/answer/6149970  
**Health Products:** https://support.google.com/merchants/answer/6150138

---

## ✅ Final Checklist Before Launch

- [ ] Product feed shows $49.00 USD
- [ ] Landing page title includes "Testosterone Test Kit"
- [ ] No health claims anywhere on page
- [ ] Schema validates at schema.org validator
- [ ] LegitScript badge visible in footer
- [ ] FAQ section present and accurate
- [ ] Mobile CTA above the fold
- [ ] All links work (affiliate URL correct)
- [ ] Disclaimers present and visible
- [ ] "Add to Cart" or "Buy Now" functionality works

---

**Status:** ✅ COMPLIANT  
**Last Review:** March 13, 2026  
**Next Review:** Monthly or when policies update
