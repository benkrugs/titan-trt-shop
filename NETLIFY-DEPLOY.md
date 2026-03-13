# Netlify Deployment Guide - Titan TRT Google Shopping

**Status:** ✅ Ready to deploy  
**GitHub Repo:** https://github.com/benkrugs/titan-trt-shop  
**Product:** $49 Testosterone Test Kit

---

## 🚀 Quick Deploy (2 Minutes)

### Step 1: Log into Netlify
1. Go to https://app.netlify.com/
2. Log in with your GitHub account

### Step 2: Import Repository
1. Click **"Add new site"** → **"Import an existing project"**
2. Choose **"Deploy with GitHub"**
3. Authorize Netlify (if first time)
4. Search for: **"titan-trt-shop"**
5. Click on the repo

### Step 3: Configure Build Settings
**These should auto-populate from netlify.toml:**

```
Base directory: (leave blank)
Build command: echo 'Static site - no build needed'
Publish directory: .
```

**✅ Just click "Deploy site"** - settings are already configured!

### Step 4: Get Your Live URL
- Netlify will deploy in 30-60 seconds
- You'll get a URL like: `https://amazing-name-123456.netlify.app`
- You can customize this to: `https://titan-trt-test.netlify.app`

---

## 🎨 Customize Site Name (Optional)

1. Go to **Site settings** → **General**
2. Under **Site details**, click **"Change site name"**
3. Enter: `titan-trt-test` (or your preferred name)
4. Click **Save**
5. Your URL is now: `https://titan-trt-test.netlify.app`

---

## 🔗 Add Custom Domain (Optional)

If you want to use a custom domain:

1. Buy domain (e.g., `titantrttest.com`)
2. In Netlify: **Domain settings** → **Add custom domain**
3. Enter your domain
4. Follow DNS instructions (update nameservers or add CNAME)
5. Wait 24-48 hours for DNS propagation
6. Free HTTPS certificate auto-provisioned

---

## ✅ Verify Deployment

After deployment, check:

### 1. Page Loads
- [ ] Site loads at your Netlify URL
- [ ] Mobile responsive (test on phone)
- [ ] All sections visible

### 2. Schema Markup
Test at: https://validator.schema.org/
- [ ] Product schema validates
- [ ] FAQ schema validates
- [ ] Organization schema validates

### 3. Google Shopping Compliance
- [ ] No health claims visible
- [ ] Price shows as $49 (one-time)
- [ ] No subscription/monthly language
- [ ] LegitScript badge in footer
- [ ] Disclaimers present

### 4. CTAs Work
- [ ] All buttons link to correct affiliate URL
- [ ] Tracking parameter present: `sub1=shop`

---

## 📊 Google Merchant Center Setup

### Step 1: Create Product
1. Log into Google Merchant Center
2. Click **"Products"** → **"Add products"**
3. Choose **"Add products one by one"**

### Step 2: Fill Product Details

```
Product title: Titan Testosterone Test Kit - $49
Description: Comprehensive testosterone lab testing with 12+ biomarkers, online clinician consultation, and personalized health assessment. Normally $149.

Price: 49.00 USD
Sale price: (leave blank or same as price)
Availability: In stock
Condition: New
Brand: Titan

GTIN: (leave blank if you don't have one)
MPN: (leave blank or use: TITAN-TEST-KIT-001)

Product link: https://[your-netlify-url].netlify.app
Image link: https://jointitan.com/images/test-kit.jpg
(Or upload your own product image)

Product category: Health & Beauty > Health Care > Medical Tests & Monitors
Google product category ID: 6218

Adult: Yes (healthcare product)
Age group: Adult
Gender: Male
```

### Step 3: Submit for Review
- Click **"Save"**
- Google will review (usually 1-3 business days)
- Check for any disapprovals in Merchant Center

---

## 🎯 Google Shopping Campaign Setup

### Step 1: Create Campaign
1. Go to Google Ads
2. Click **"+ New campaign"**
3. Choose goal: **"Sales"** or **"Leads"**
4. Campaign type: **"Shopping"**
5. Select your Merchant Center account

### Step 2: Campaign Settings

```
Campaign name: Titan TRT Test Kit - Shopping
Bidding: Manual CPC (start) or Target ROAS (later)
Daily budget: $50-100 (recommend starting at $75)
Networks: Google Search only (uncheck Search Partners initially)
Locations: United States
Language: English
```

### Step 3: Ad Group Settings

```
Ad group name: All Products
Bid: $1.50-3.00 CPC (adjust based on performance)
```

### Step 4: Negative Keywords

Add these to prevent wasted spend:

```
free
free test
free testosterone
prescription only
illegal
steroids
cheap
scam
reviews (if not using review extensions)
without doctor
no prescription
```

### Step 5: Launch
- Review everything
- Click **"Publish"**
- Ads go live after Google review (usually within 24 hours)

---

## 📈 Performance Monitoring

### Daily Checks (First 7 Days)
- [ ] Check impressions (product showing?)
- [ ] Check clicks (any traffic?)
- [ ] Check disapprovals (any issues?)
- [ ] Check conversion tracking (sales recording?)

### Key Metrics to Watch

**CTR (Click-Through Rate):**
- Target: 1-3%
- If lower: Improve image/title in product feed

**Conversion Rate:**
- Target: 3-6%
- If lower: Review landing page (A/B test CTAs)

**CPC (Cost Per Click):**
- Expected: $8-15 for TRT niche
- Adjust bids based on performance

**ROAS (Return on Ad Spend):**
- Target: 3:1 or higher
- With $350 CPA, break-even at ~1.75:1 ROAS

---

## 🔧 Troubleshooting

### Product Disapproved: "Misleading Claims"
**Fix:** Check landing page for any health benefit language
**Action:** Remove claims, request review in Merchant Center

### Product Disapproved: "Unclear Pricing"
**Fix:** Ensure $49 is clearly visible on page
**Action:** Update product feed with exact price match

### Product Disapproved: "Healthcare Product"
**Fix:** Add proper disclaimers to landing page
**Action:** Ensure LegitScript badge is visible

### No Impressions After 48 Hours
**Possible Causes:**
- Product not approved yet
- Bids too low
- Product not competitive for keywords

**Fix:** Check product status, raise bids to $3-5 initially

### High Clicks, No Conversions
**Possible Causes:**
- Landing page issues
- Wrong audience
- Affiliate link broken

**Fix:** Test affiliate URL, review analytics, check mobile UX

---

## 📞 Support Resources

**Netlify Docs:** https://docs.netlify.com/  
**Google Merchant Center:** https://support.google.com/merchants/  
**Google Shopping Policies:** https://support.google.com/merchants/answer/6149970  
**Schema Validator:** https://validator.schema.org/

---

## ✅ Pre-Launch Checklist

### Netlify Deployment
- [ ] Site deployed to Netlify
- [ ] Custom URL configured (optional)
- [ ] HTTPS enabled (auto)
- [ ] All pages load correctly
- [ ] Mobile responsive confirmed

### Google Compliance
- [ ] Schema validates (all 3 types)
- [ ] No health claims on page
- [ ] Price clearly $49 (one-time)
- [ ] Disclaimers present
- [ ] LegitScript badge visible

### Google Merchant Center
- [ ] Product created
- [ ] Title/description accurate
- [ ] Price matches landing page ($49)
- [ ] Image uploaded
- [ ] Category correct (Medical Tests)
- [ ] Adult flag set to Yes

### Google Ads Campaign
- [ ] Shopping campaign created
- [ ] Budget set ($50-100/day)
- [ ] Negative keywords added
- [ ] Conversion tracking installed (if possible)
- [ ] Campaign published

---

## 🎯 Expected Performance (First 30 Days)

### Conservative Estimates:
```
Daily budget: $75
Avg CPC: $12
Daily clicks: ~6 clicks
CTR: 2%
Conversion rate: 4%
Daily conversions: 0.24 (1-2 per week)
Monthly conversions: 7-8
Cost per conversion: ~$300
```

### Optimistic Estimates:
```
Daily budget: $100
Avg CPC: $10
Daily clicks: 10 clicks
CTR: 3%
Conversion rate: 6%
Daily conversions: 0.6 (4-5 per week)
Monthly conversions: 18-20
Cost per conversion: ~$165
```

**Goal:** Achieve $200-250 cost per conversion by Month 3

---

## 🚀 Launch Timeline

**Day 1:**
- Deploy to Netlify ✅
- Create product in Merchant Center

**Day 2-3:**
- Wait for product approval
- Set up Google Ads campaign (don't publish yet)

**Day 4:**
- Product approved
- Launch Shopping campaign
- Monitor hourly for first day

**Week 1:**
- Daily monitoring
- Adjust bids based on performance
- Add negative keywords as needed

**Week 2-4:**
- Optimize based on data
- Test bid adjustments
- Scale budget if profitable

---

**Ready to deploy!** Follow the steps above and you'll be live in minutes. 🚀
