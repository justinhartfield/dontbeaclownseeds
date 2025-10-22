# DontBeAClownSeeds.com

**Landing Page Funnel to Official Cannabis Seeds**

A complete rebrand transformation from the original weed.de medical cannabis site to a cannabis seeds lead capture funnel that redirects to officialcannabisseeds.com.

## 🎯 Project Overview

This landing page serves as a lead capture funnel:
- **Domain**: dontbeaclownseeds.com
- **Purpose**: Capture qualified leads for cannabis genetics
- **Redirect**: Leads to officialcannabisseeds.com after form submission
- **Campaign**: "Don't Be A Clown" video series with transformation messaging

## ✅ Complete Transformation Features

### 🎬 Video Content
- **7 Updated Videos** with new Vimeo sources:
  - Trailer: `vimeo.com/1129513454`
  - Long Cut: `vimeo.com/1129513180`
  - Transformation: `vimeo.com/1129513093`
  - Sign Spinning: `vimeo.com/1129513419`
  - Intervention 1: `vimeo.com/1129513337`
  - Reservoir: `vimeo.com/1129513367`
  - Intervention 2: `vimeo.com/1129513141`

### 🌐 Language & Branding
- **English Only** (German language support removed)
- **Cannabis Seeds Focus** (medical cannabis messaging replaced)
- **Official Cannabis Seeds Integration** (branding and messaging)
- **"Every Strain Tells a Story"** tagline

### 📊 Lead Capture System
- **Age Verification Popup** with enhanced lead capture
- **Email Collection** with validation
- **Newsletter Opt-in** (pre-checked for max conversions)
- **UTM Tracking** for campaign attribution
- **Klaviyo Ready** data structure

## 🚀 **Deployment Instructions**

### **Option 1: Netlify Drag & Drop**
1. Go to [netlify.com](https://netlify.com)
2. Drag and drop this entire folder to the deployment area
3. Your site will be live immediately

### **Option 2: Git Integration**
1. Upload this folder to a GitHub repository
2. Connect the repository to Netlify
3. Deploy automatically with git pushes

### **Option 3: Netlify CLI**
```bash
npm install -g netlify-cli
netlify deploy --prod --dir .
```

## 📁 **Package Contents**

### **Core Files**
- `index.html` - Main landing page with embedded age verification
- `netlify.toml` - Netlify configuration with optimizations
- `_redirects` - URL routing and SEO redirects
- `README.md` - This deployment guide

### **Assets Directory**
- `/assets/` - All CSS, JavaScript, images, and videos
- Optimized for fast loading and caching

### **Additional Pages**
- `about.html` - About page
- `contact.html` - Contact page  
- `privacy.html` - Privacy policy
- `terms.html` - Terms of service

## 🎯 **Age Verification Features**

### **Lead Capture System**
- Email collection with validation
- Age confirmation (18+ required)
- Newsletter opt-in (pre-checked for max conversions)
- Complete data structure for Klaviyo integration

### **Session Management**
- Verified users bypass popup on return visits
- Secure session storage
- Lead data stored in localStorage for retargeting

### **Video Protection**
- Content locked behind age verification
- Automatic video playback after verification
- Professional popup design with weed.de branding

## 📊 **Lead Data Structure**

```json
{
  "email": "user@email.com",
  "ageVerified": true,
  "newsletterOptin": true,
  "timestamp": "2025-07-31T05:40:00.000Z",
  "source": "age_verification_popup"
}
```

## 🔧 **Configuration**

### **Netlify Settings**
- Build command: `echo 'Static site - no build required'`
- Publish directory: `.` (root)
- Node version: 18

### **Security Headers**
- XSS Protection enabled
- Content Security Policy configured
- Frame options set to DENY
- Referrer policy optimized

### **Performance Optimization**
- Asset caching (1 year for static assets)
- HTML caching (1 hour with revalidation)
- Immutable cache headers for versioned assets

## 🎊 **Ready for Production**

This package is **production-ready** and optimized for:
- ✅ **Lead Generation Campaigns**
- ✅ **Meta Retargeting**
- ✅ **Klaviyo Email Marketing**
- ✅ **SEO Performance**
- ✅ **Mobile Experience**

## 📞 **Support**

For technical support or customizations, contact the development team.

**Deploy and start capturing leads immediately!** 🚀

