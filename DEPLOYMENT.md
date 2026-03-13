# Titan TRT Google Shopping - Deployment Guide

**Status:** ✅ Ready to deploy to Netlify

---

## 🚀 Quick Deploy (5 minutes)

### Step 1: Connect Netlify

1. Go to **https://app.netlify.com/**
2. Click **"Add new site"** → **"Import an existing project"**
3. Choose **GitHub**
4. Select repository: **benkrugs/titan-trt-shop**

### Step 2: Configure Build Settings

Netlify will auto-detect from `netlify.toml`:

- **Build command:** `echo 'Static site - no build needed'`
- **Publish directory:** `.` (root)
- **No additional config needed** ✅

### Step 3: Deploy

1. Click **"Deploy site"**
2. Wait ~30 seconds for deployment
3. You'll get a URL like: `https://[random-name].netlify.app`

### Step 4: Add Custom Domain (Optional)

**Recommended domains:**
- `buy-titan-trt.com`
- `shop-titan-trt.com`
- `titan-trt-shop.com`
- Or subdomain: `shop.trtcomparison.com`

**To add custom domain:**
1. Go to **Site settings** → **Domain management**
2. Click **"Add custom domain"**
3. Follow DNS instructions
4. Netlify auto-provisions SSL certificate ✅

---

## 📄 What's Deployed

**Files:**
- `index.html` (main landing page)
- `legitscript-badge.webp` (trust badge)
- `README.md` (documentation)
- `netlify.toml` (deployment config)

**All CTAs link to:**
```
https://jointitan.com/?toclid=TO-2RbC8WhCGKBLFQ2J90aUB9&utm_source=theoffer&utm_campaign=94&sub1=shop
```

---

## ✅ Pre-Deployment Checklist

- [x] Mobile CTA above the fold
- [x] Titan branding (blue/orange colors)
- [x] LegitScript badge in footer
- [x] 6 CTAs throughout page
- [x] Product details + benefits
- [x] How-it-works section
- [x] Medical disclaimers
- [x] Affiliate tracking URL
- [x] GitHub repo created
- [x] Netlify config added
- [x] All files committed + pushed

---

## 📊 Google Shopping Setup

### Product Feed

Once site is live, create product in Google Merchant Center:

**Product Details:**
```
id: titan-trt-injectable
title: Titan Injectable TRT - Premium Testosterone Therapy
description: Doctor-prescribed testosterone replacement therapy. Free shipping, discreet packaging. Start for $49.
link: [YOUR NETLIFY URL]
image_link: [product image URL - optional]
price: 99.00 USD
availability: in stock
condition: new
brand: Titan
google_product_category: Health & Beauty > Health Care
```

### Shopping Campaign

**Settings:**
- Campaign type: Shopping
- Bidding: Target ROAS (start with Manual CPC)
- Budget: $50-100/day to start
- Target: United States
- Age: 25-65
- Gender: Male

**Negative Keywords:**
- free
- cheap
- discount
- coupon
- lawsuit
- scam
- side effects (unless you want info seekers)

---

## 🔧 Post-Deploy Testing

1. **Mobile Test:**
   - Open on iPhone/Android
   - Verify CTA button above fold
   - Test all 6 CTA links
   - Check LegitScript badge displays

2. **Desktop Test:**
   - Verify responsive layout
   - Test CTAs
   - Check footer links

3. **Performance Test:**
   - PageSpeed Insights: https://pagespeed.web.dev/
   - Target: 90+ mobile score (static HTML should be fast)

4. **Tracking Test:**
   - Click through to Titan
   - Verify tracking parameters in URL
   - Check TheOffer dashboard for click

---

## 📈 Monitoring

**Track these metrics:**
- Impressions (Google Shopping)
- Clicks (Google Ads)
- Click-through rate (CTR)
- Conversion rate (Netlify analytics or Google Analytics)
- Cost per acquisition (CPA)

**Expected performance:**
- CTR: 1-3% (Google Shopping)
- Landing page CVR: 3-6%
- CPC: $8-15 (TRT niche)

---

## 🎯 Optimization Tips

### Week 1: Baseline
- Let campaign run with minimal changes
- Gather 100+ clicks minimum
- Monitor which search terms convert

### Week 2-4: Optimize
- Add negative keywords for non-converters
- Adjust bids on high-performing products
- Test different ad copy (title/description)
- A/B test landing page variants (optional)

### Month 2+: Scale
- Increase budget on profitable campaigns
- Launch remarketing to previous visitors
- Test different product images
- Expand to other TRT products (if available)

---

## 🆘 Troubleshooting

**Badge not showing?**
- Check `legitscript-badge.webp` uploaded correctly
- Verify file path in HTML
- Try hard refresh (Cmd+Shift+R / Ctrl+Shift+R)

**CTAs not tracking?**
- Verify affiliate URL has all parameters
- Check TheOffer dashboard
- Test click manually

**Mobile CTA below fold?**
- Check viewport settings
- Test on real device (not just browser resize)
- Hero section should be 100vh max

**Slow load times?**
- Optimize images (compress badge)
- Check Netlify deployment status
- Use CDN (Netlify has built-in CDN)

---

## 📝 Change Log

**Version 1.0 - March 13, 2026**
- Initial deployment
- LegitScript badge added
- Titan branding implemented
- 6 CTAs with affiliate tracking
- Mobile-first responsive design

---

## 🔗 Resources

- **GitHub Repo:** https://github.com/benkrugs/titan-trt-shop
- **Netlify Docs:** https://docs.netlify.com/
- **Google Shopping Guide:** https://support.google.com/merchants/
- **Titan Affiliate:** https://jointitan.com

---

**Questions?** Check README.md or contact support.

**Ready to launch!** 🚀
