# Cyber Portfolio '99 🔮

A retro-style Y2K inspired personal portfolio celebrating the aesthetic of late-90s web design. This is where I host fun, experimental projects to share on X.

## What This Project Does

This is a personal portfolio website built as a nostalgic tribute to the internet of the late 1990s and early 2000s. It showcases projects and experiments in a fully functional single-page website that recreates the look and feel of the pre-modern web era—complete with marquees, neon colors, and authentic retro charm.

**Features:**
- Authentic 90s aesthetic with vibrant neon colors (cyan, pink, yellow, gold on deep navy backgrounds)
- Scrolling marquees with retro fonts (Comic Sans, Courier New, Impact)
- Embedded NES-era background music (Batman stage 1 MIDI)
- Persistent visitor counter using browser localStorage
- Links to fun projects:
  - **SecondShelf**: A Chrome Web Extension for saving and organizing reading
  - **I'm Feeling Grokky**: A retro portal for random learning adventures via Grokipedia
  - **I'm Feeling Martian**: A retro portal for checking Mars weather conditions
  - **PainCast**: A web app for predicting daily chronic pain levels
- Fully responsive design that works on modern devices while hiding sidebars on mobile
- Animated GIFs and spinning elements for maximum late-90s charm

## Technologies Used

- **HTML5**: Semantic markup with retro flair
- **CSS3**: Custom utility-based styling system for the 90s aesthetic
- **JavaScript**: Vanilla JS for the persistent visitor counter using localStorage API
- **Bootstrap 5.3.3**: For responsive grid layout and mobile responsiveness
- **GitHub Pages**: Hosted at tommi.fun via custom CNAME

## About This Portfolio

This is my personal portfolio space where I host fun, experimental projects to share on X. Rather than a traditional professional portfolio, it's a creative outlet for showcasing side projects, tools, and web experiments—all wrapped in a Y2K aesthetic that reflects my vibe on the platform. The retro design is intentional and central to the concept, celebrating early web culture while remaining fully functional and accessible on modern devices.

## Notable Design Choices

### Intentional Retro Authenticity
The 90s aesthetic isn't ironic—it's the core concept. The site embraces deprecated HTML elements (marquee), deliberately uses Comic Sans and other classic 90s fonts, and features a neon color palette with deep navy backgrounds. This is a celebration, not a parody.

### Modern Foundation with Retro Veneer
Despite the nostalgic appearance, the underlying architecture is modern and functional:
- Uses Bootstrap 5 for proper responsive grid layout
- localStorage API for persistent visitor counter (instead of server-side CGI-BIN)
- Proper semantic HTML5 with accessibility meta tags
- Works flawlessly on modern browsers and devices

### Self-Aware Design Language
Throughout the site, there are subtle nods to the anachronistic nature:
- "Optimized for Netscape Navigator, CRT monitors, and pure dial-up patience"
- "This site may look like it's built with tables, but it really wasn't!"
- "(Count stored locally because CGI-BIN is down)" — the visitor counter explanation
- Project descriptions use playful language about "cyber tools" and "top secret projects"

### Utility-First CSS System
Custom CSS defines reusable utility classes for consistency:
- **Font families**: .font-comic, .font-courier, .font-impact, .font-verdana
- **Retro sizes**: .fs-7-retro (3rem) through .fs-3-retro (1rem)
- **Neon colors**: .text-retro-cyan, .text-retro-pink, .text-retro-gold, .text-retro-yellow, .text-retro-light-cyan, .text-retro-light-pink, .text-retro-grey

This approach makes the retro theme easy to maintain and extend.

### Minimal Dependencies
- No build tools, no webpack, no npm overhead
- Single HTML file, single CSS file, single JavaScript file
- Bootstrap loaded via CDN for responsive grid only
- All assets are either local or from reliable CDNs
- Everything is self-contained and easy to modify

### Responsive Without Compromise
The layout adapts gracefully to mobile devices while maintaining the retro aesthetic:
- Sidebar elements hide on smaller screens
- Main content area reflows cleanly
- All interactive elements remain accessible
- Touch-friendly link sizes

---

Status: A joyful, fully functional personal portfolio for sharing experimental web projects on X. Built with authentic late-90s design sensibilities using modern web standards. 🚀