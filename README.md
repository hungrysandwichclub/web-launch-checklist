
# 🚀 HSC Site Launch Checklist 🚀

A simple hitlist to make sure launch day goes smoothly. Good luck!


# Housekeeping 🏚

- [ ] Favicon is showing.
- [ ]   404 Page is set up.
- [ ]  Logo links back to the homepage.
- [ ]  There are no broken links - Use an automated tool such as integrity.
- [ ]  Timezone is set correctly.
- [ ]  Client user accounts has been set up.
- [ ]  SSL Certificate has been set up.
- [ ]  Analytics tracking is in place if used.



# Humans 😎

- [ ]  Copy makes sense - have someone new read this before launch.
- [ ]   Spelling has been checked.
- [ ]   Constant visual style for buttons, links and UI elements.
- [ ]  Contact Details are correct and working.
- [ ]   A privacy policy in place if cookies are used, or if data is processed.
- [ ]   Website is loading on all current desktop browsers  (Safari, Firefox, Chrome, IE11, EDGE) unless otherwise agreed with the client. - [https://browserstack.com](https://www.browserstack.com/)
- [ ]   Design files have been compared to staging site.



# SEO 🤖

- [ ]   Robots.txt set to prevent crawling on staging, allow on live site.
- [ ]   Sitemap has been set up.
- [ ]   301 Redirects in place.
- [ ]   URL Structure is consistent.



# Assets: 🖼

- [ ]    Images use srcset with appropriate sizes.
- [ ]   Images are lazyloaded - [https://github.com/aFarkas/lazysizes](https://github.com/aFarkas/lazysizes).
- [ ]  Images served efficiently - Cloudinary/Imager
- [ ]  Images are served through a CDN
- [ ]  Image have alt tags
- [ ]  Has a websafe font been matched to help reduce FLOUT - [https://meowni.ca/font-style-matcher/](https://meowni.ca/font-style-matcher/)
- [ ]   Comments are removed for production



# Deployment: 📦

- [ ]    Develop and Master branches have auto-deploy hooks to staging and live.
- [ ]   Build for production runs on deploy
- [ ]   There is 48 hours before launch if DNS changes are required  (consider dropping TTL)
  


# Performance: ️⚡

- [ ]   Site has been tested with GTMetrix and Lighthouse
- [ ]   Site has been tested on fast 3g conditions
- [ ]   Scripts and stylesheets are minified as part of the build process
- [ ]   Critical styles are extracted and inlined. [https://github.com/filamentgroup/loadCSS](https://github.com/filamentgroup/loadCSS)
 
 

# Access 🤘

- [ ]   Content has logical tabindex
- [ ]   ‘Skip to main content’ link is in place
- [ ]   There is sufficient contrast between background and foreground
- [ ]   Focus styles have been tested
- [ ]   Site has been used with only a keyboard



# If you only check one thing 🔥
- [ ]  I'm not launching on a Friday



# Also check these:
[https://frontendchecklist.io/](https://frontendchecklist.io/)  
[https://github.com/drublic/checklist](https://github.com/drublic/checklist)
