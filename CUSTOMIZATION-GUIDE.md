# Quick Customization Guide

## 🎯 5-Minute Setup

### Step 1: Update Your Game Information
Find this section in `index.html` (around line 162):

```html
<h5>Cyber Slum Tycoon</h5>
<p>Our flagship title currently in early development...</p>
```

Replace with your actual game name and description!

### Step 2: Add Your Email
Find this in the footer (around line 348):

```html
<p style="color: #999; margin-top: 20px;">Email: contact@adaviarcore.com</p>
```

Change to your real email address.

### Step 3: Link Your Social Media
Find the social icons (around line 344) and update the `href="#"` with your actual social media URLs:

```html
<a href="https://x.com/Adaviarcore">
<a href="https://instagram.com/Adaviar">
```

## 🎨 Common Customizations

### Change the Studio Name
Search and replace "Adaviar Games" with your studio name throughout `index.html`.

### Change Color Scheme
The template uses a blue accent color (#00d4ff). To change it:
1. Open `css/style.css`
2. Search for `#00d4ff`
3. Replace with your brand color

### Add a Downloadable Press Kit
Add this to your mission section:

```html
<a href="files/press-kit.zip" class="site-btn" style="margin-top: 15px;">Download Press Kit</a>
```

### Add Google Analytics
Before the closing `</head>` tag, add:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=YOUR-ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'YOUR-GA-ID');
</script>
```

## 🖼️ Image Sizes Reference

For best results, use these image dimensions:
- **Logo**: 200x60px (transparent PNG)
- **Hero Banners**: 1920x800px
- **Feature Images**: 600x400px
- **Game Screenshots**: 800x600px
- **Mission/About Images**: 800x600px
- **Roadmap Images**: 600x400px

## 🚨 Common Issues

**Q: My images aren't showing**
A: Make sure the image paths in `index.html` match your actual file names in the `img/` folder.

**Q: The slider isn't working**
A: Check that all JavaScript files are present in the `js/` folder.

**Q: Colors look different**
A: Clear your browser cache (Ctrl+F5 on Windows, Cmd+Shift+R on Mac).

## 📱 Mobile Testing

Before going live, test your site on mobile:
1. Open Chrome Developer Tools (F12)
2. Click the device toolbar icon
3. Test on different screen sizes
4. Make sure text is readable and buttons are clickable

## ✨ Pro Tips

1. **Compress your images** before uploading (use TinyPNG.com)
2. **Test your contact form** to make sure emails arrive
3. **Add your site to Google Search Console** for SEO
4. **Create a custom 404 page** for better UX
5. **Set up a custom domain** (optional but professional)

---

Need more help? Ask AI:
"I have the Adaviar Games template and want to [describe what you want]"
