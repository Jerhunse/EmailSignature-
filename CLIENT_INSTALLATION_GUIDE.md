# Email Signature Installation Guide for Client

## 🎯 **IMPORTANT: Ensuring All Images and Icons Work Properly**

Your email signature has been optimized to work reliably across all email clients. Here's how to ensure everything displays correctly:

## 📁 **Files You Need**

1. **`email-signature-gmail-embedded.html`** - This is your main signature file
2. **`alexis.jpg`** - Your profile photo (keep this in the same folder)

## 🔧 **Installation Options**

### **Option 1: Gmail (Recommended)**

1. **Open Gmail** in your web browser
2. **Go to Settings** (gear icon in top right)
3. **Click "See all settings"**
4. **Scroll down to "Signature"** section
5. **Click the "+" to create a new signature**
6. **Open the `email-signature-gmail-embedded.html` file** in a text editor
7. **Copy ALL the code** (from `<!-- Gmail-optimized email signature...` to the end)
8. **Paste it into the signature box** in Gmail
9. **Save your changes**

### **Option 2: Using Browser Inspect Element (If Gmail blocks the signature)**

1. **Open Gmail** and compose a new email
2. **Right-click in the compose area** and select "Inspect Element"
3. **Find the signature area** in the HTML (look for `<div class="Am Al editable">`)
4. **Right-click on that element** and select "Edit as HTML"
5. **Paste the signature code** from `email-signature-gmail-embedded.html`
6. **Press Enter** to save

## ✅ **What's Already Embedded (No External Dependencies)**

✅ **All social media icons** (Facebook, Instagram, YouTube)  
✅ **All contact icons** (phone, email, website)  
✅ **eXp logo**  
✅ **Profile photo** (uses local `alexis.jpg` file)  

## 🚨 **Critical Steps for Image Display**

### **For the Profile Photo to Work:**

1. **Keep `alexis.jpg` in the same folder** as your signature file
2. **Upload `alexis.jpg` to a web server** (like your website) and update the image source
3. **OR use a cloud storage service** like Google Drive, Dropbox, or OneDrive:
   - Upload `alexis.jpg` to your cloud storage
   - Get the sharing link
   - Replace `alexis.jpg` in the signature code with the full URL

### **Alternative: Use a Web-Hosted Image**

If you want the profile photo to work without local files:

1. **Upload `alexis.jpg` to your website** (e.g., `https://www.thelexgrp.com/images/alexis.jpg`)
2. **Replace `alexis.jpg`** in the signature code with the full URL
3. **This ensures the image works in all email clients**

## 🔍 **Testing Your Signature**

1. **Send a test email** to yourself
2. **Check on different devices** (computer, phone, tablet)
3. **Test in different email clients** (Gmail, Outlook, Apple Mail)
4. **Verify all links work** (click each social media icon and contact info)

## 🛠️ **Troubleshooting**

### **If Images Don't Show:**
- Make sure `alexis.jpg` is in the same folder as the HTML file
- Try uploading the image to your website and using the full URL
- Check that your email client allows images

### **If Icons Don't Display:**
- The icons are embedded as SVG data, so they should work everywhere
- If they don't show, try refreshing the email or checking your email client's image settings

### **If Links Don't Work:**
- Verify all URLs are correct in the signature code
- Test each link by clicking on it
- Make sure your email client allows clickable links

## 📞 **Need Help?**

If you encounter any issues:
1. **Try the browser inspect element method** (Option 2 above)
2. **Upload the profile image to your website** and use the full URL
3. **Test in different email clients** to see which works best

## 🎨 **Customization**

To change any information:
- **Phone numbers**: Update the `href="tel:..."` values
- **Email address**: Update the `href="mailto:..."` value  
- **Website**: Update the `href="https://..."` value
- **Social media links**: Update the respective URLs

---

**Your signature is now ready to use!** All icons are embedded and will display reliably across email clients. Just make sure the profile photo is accessible via a web URL for the best compatibility. 