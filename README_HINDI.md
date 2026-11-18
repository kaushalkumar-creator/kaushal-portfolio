# Kaushal Kumar — Creative Portfolio Website

यह एक responsive, static portfolio website है। इसे चलाने के लिए कोई paid backend या database नहीं चाहिए।

## Files
- `index.html` — वेबसाइट का content और structure
- `style.css` — design और responsive layout
- `script.js` — mobile menu और current year
- `assets/favicon.svg` — website icon

## पहले ये चीजें अपडेट करें
1. `index.html` में About section का परिचय अपने हिसाब से बदलें।
2. Skills और Tools में केवल वही चीजें रखें जिनमें आप वास्तव में काम करते हैं।
3. Instagram link `https://www.instagram.com/kaushal_kumar_editz/` को verify करें।
4. Concept project cards को अपने असली videos से बदलें। अभी वे साफ तौर पर concept / planned दिखाए गए हैं।
5. अपना email जोड़ना हो तो Contact section में mailto link जोड़ें।

## अपने वीडियो कैसे जोड़ें
हर project card में visual placeholder की जगह यह markup लगा सकते हैं:

```html
<video controls playsinline preload="metadata" poster="assets/my-project-poster.jpg">
  <source src="assets/my-project.mp4" type="video/mp4">
</video>
```

वीडियो को `assets/` folder में रखें और `src` में सही filename लिखें। बेहतर loading के लिए MP4 (H.264) और compressed video इस्तेमाल करें। शुरुआत में 3–5 छोटे samples पर्याप्त हैं।

## Free Hosting: GitHub Pages
1. GitHub पर sign in करें या account बनाएँ।
2. नया public repository बनाएँ, उदाहरण: `kaushal-portfolio`.
3. इस ZIP की files extract करके repository के root में upload करें। ध्यान रहे `index.html` root में हो।
4. GitHub repository में **Settings → Pages** खोलें।
5. **Build and deployment → Deploy from a branch** चुनें।
6. Branch `main` और folder `/ (root)` चुनकर Save करें।
7. GitHub कुछ समय में website URL देगा: `https://YOUR-USERNAME.github.io/kaushal-portfolio/`

GitHub Pages static website hosting के लिए है। इस version में कोई login, database या private upload dashboard नहीं है।

## Before sharing with clients
- मोबाइल पर पूरा page test करें।
- Instagram link खोलकर verify करें।
- सभी sample videos खुद के हों या उनके उपयोग की अनुमति हो।
- Fake client names, testimonials या results न जोड़ें।
- Contact email जोड़ने के बाद test inquiry भेजकर देखें।
