# 🚀 QUICK LAUNCH CHECKLIST
## Secure Construction So Ltd Website

### CRITICAL - MUST DO BEFORE LAUNCH

#### 1. Contact Form Setup ⚠️
- [ ] Sign up for form service (Formspree.io recommended)
- [ ] Get your form ID
- [ ] Replace `YOUR_FORM_ID` in contact.html line 82
- [ ] Test form submission
- [ ] Verify emails are received at secureconstruction.so@gmail.com

#### 2. Images 📸
- [ ] Add company logo to header (all pages)
- [ ] Replace project image placeholders (6 projects)
- [ ] Add hero background image (home page)
- [ ] Create favicon (32x32px)

#### 3. Google Maps 🗺️
- [ ] Get Google Maps embed code for office location
- [ ] Replace map placeholder on contact.html
- [ ] Test map display and directions link

#### 4. Domain & Hosting 🌐
- [ ] Purchase domain name (e.g., secureconstruction.ie)
- [ ] Set up web hosting
- [ ] Upload all website files
- [ ] Configure SSL certificate (HTTPS)
- [ ] Test website loads correctly

### IMPORTANT - BEFORE GOING LIVE

#### SEO Setup
- [ ] Create Google Business Profile
- [ ] Set up Google Analytics
- [ ] Set up Google Search Console
- [ ] Submit sitemap to Google

#### Testing
- [ ] Test on mobile phones (iPhone & Android)
- [ ] Test contact form submission
- [ ] Test all phone number links (click-to-call)
- [ ] Test email links
- [ ] Check all pages load correctly
- [ ] Verify navigation menu works

#### Content Review
- [ ] Verify phone number: 0862709299
- [ ] Verify email: secureconstruction.so@gmail.com
- [ ] Verify address: Unit 5A, Aston Green, Aston Village, Drogheda, Co. Louth
- [ ] Review all service descriptions
- [ ] Check for typos

### RECOMMENDED - FIRST WEEK

#### Marketing Setup
- [ ] Add website to business cards
- [ ] Add website to email signature
- [ ] Share website on social media
- [ ] Update Google Business Profile with website
- [ ] Add website to any existing directories

#### Monitoring
- [ ] Check Google Analytics daily
- [ ] Monitor form submissions
- [ ] Test call tracking
- [ ] Check for any broken links

### ONGOING - MONTHLY

- [ ] Add new project photos to Projects page
- [ ] Add new testimonials as received
- [ ] Update any service offerings
- [ ] Review Google Analytics reports
- [ ] Check Google Search Console for errors

---

## 📞 CONTACT FORM FIX - DETAILED STEPS

### Option 1: Formspree (Easiest - Recommended)

1. Go to https://formspree.io/
2. Sign up for free account
3. Create new form
4. Copy your Form ID (looks like: xpzgvwxy)
5. In contact.html, line 82, replace:
   ```html
   <form class="contact-form" id="contactForm" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
   ```
   with:
   ```html
   <form class="contact-form" id="contactForm" action="https://formspree.io/f/xpzgvwxy" method="POST">
   ```
6. Test by submitting the form
7. Check secureconstruction.so@gmail.com for test email

### Option 2: Web3Forms (Alternative)

1. Go to https://web3forms.com/
2. Enter email: secureconstruction.so@gmail.com
3. Get access key
4. Add to form as hidden field
5. Change action to: https://api.web3forms.com/submit

### Option 3: Your Hosting Provider

Contact your hosting provider - most offer form-to-email services.

---

## 🖼️ IMAGE SPECIFICATIONS

### Logo
- **Size:** 200x60px (header) and 400x120px (footer)
- **Format:** PNG with transparency
- **Background:** Transparent
- **Add to:** All 6 HTML files in header

### Project Photos (6 needed)
- **Size:** Minimum 1200x800px each
- **Format:** JPG
- **Quality:** High resolution, compressed to ~200KB
- **Update:** projects.html - replace all placeholder divs

### Hero Background
- **Size:** 1920x800px
- **Format:** JPG
- **Quality:** Web-optimized ~300KB
- **Add to:** index.html hero section

### Favicon
- **Size:** 32x32px
- **Format:** PNG or ICO
- **Add to:** All HTML files in <head> section:
  ```html
  <link rel="icon" type="image/png" href="favicon.png">
  ```

---

## 🌐 DOMAIN SETUP

### Recommended Domain Names (Check Availability)
1. secureconstruction.ie (Best - Irish domain)
2. secureconstructionso.ie
3. secureconstruction.com
4. secureconstructionltd.ie

### Hosting Recommendations (Ireland)
- Blacknight.com (Irish hosting)
- Hosting Ireland
- Vodien
- Or international: SiteGround, Bluehost

### After Domain Purchase
1. Point domain to hosting nameservers
2. Set up email forwarding (if not using Google Workspace)
3. Install SSL certificate (usually free with hosting)
4. Upload all website files via FTP or hosting control panel

---

## 📱 GOOGLE BUSINESS PROFILE SETUP

### Information to Enter
- **Business Name:** Secure Construction So Ltd
- **Category:** Construction Company (Primary)
- **Additional Categories:** 
  - Fire Protection Service
  - Scaffolding Service
  - Building Materials Supplier
- **Address:** Unit 5A, Aston Green, Aston Village, Drogheda, Co. Louth
- **Phone:** 0862709299
- **Website:** [Your new domain]
- **Service Area:** Drogheda, Co. Louth, and surrounding areas
- **Hours:** 
  - Monday-Friday: 8:00 AM - 6:00 PM
  - Saturday: 9:00 AM - 2:00 PM
  - Sunday: Closed
- **Description:** Use the "About" text from website

### Photos to Add (10+)
- Company logo
- Office exterior
- Team photos
- Project photos
- Services photos

---

## ⚡ QUICK WINS - FIRST WEEK

1. **Get First Review** - Ask happy clients to leave Google review
2. **Social Media** - Share website launch post (if applicable)
3. **Email Signature** - Add website link
4. **Business Cards** - Update or order new ones with website
5. **Invoice/Quote Templates** - Add website footer

---

## 🎯 SUCCESS TRACKING

### Week 1 Goals
- [ ] 50+ website visitors
- [ ] 2+ contact form submissions
- [ ] 5+ phone calls from website

### Month 1 Goals
- [ ] 500+ website visitors
- [ ] 10+ quote requests
- [ ] 20+ phone calls
- [ ] 5+ Google Business Profile reviews

### Check These Weekly
- Google Analytics visitor numbers
- Contact form submissions (check email)
- Google Business Profile insights
- Search Console ranking positions

---

## 🆘 TROUBLESHOOTING

### Form Not Working?
1. Check form action URL is correct
2. Verify email address in form service
3. Check spam folder for test submissions
4. Try alternative form service

### Website Not Loading?
1. Check domain DNS settings (24-48hr propagation)
2. Verify hosting account is active
3. Check files uploaded to correct directory
4. Clear browser cache and try again

### Not Showing in Google?
1. Submit sitemap to Search Console
2. Request indexing for main pages
3. Add website to Google Business Profile
4. Be patient - takes 1-2 weeks for new sites

### Mobile Menu Not Working?
1. Check js/script.js file is uploaded
2. Verify file path is correct in HTML
3. Test on different mobile browsers
4. Check browser console for errors

---

## 📞 SUPPORT CONTACTS

- **Domain Issues:** Contact your domain registrar
- **Hosting Issues:** Contact your hosting provider
- **Form Issues:** Formspree or Web3Forms support
- **Google Business:** Google Business support
- **Website Updates:** Edit HTML files and re-upload

---

**Print this page and check off items as you complete them!**

**Need help?** Refer to the full README.md for detailed instructions.

**Last Updated:** February 4, 2026
