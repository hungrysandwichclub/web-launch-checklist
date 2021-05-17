
# 🚀 HSC Site Launch Checklist 🚀

A simple hitlist to make sure launch day goes smoothly. Good luck!


# Housekeeping 🏚

- [ ]  Client user accounts have been set up.
- [ ]  Timezone is set correctly.
- [ ]  SSL Certificate has been set up.
- [ ]  Favicon is showing.
- [ ]  404 Page is set up.
- [ ]  Logo links back to the homepage.
- [ ]  There are no broken links - [Integrity - App](https://peacockmedia.software/mac/integrity/free.html)
- [ ]  Any required analytics tracking is in place.



# Humans 😎

- [ ]  Somebody new has read through the site's copy. 
- [ ]  Spelling has been checked.
- [ ]  There is a constant visual style for buttons, links and UI elements.
- [ ]  Contact Details are correct and working.
- [ ]  A privacy policy in place if cookies are used or data is processed.
- [ ]  Website is loading on all current desktop browsers  (Safari, Firefox, Chrome, Edge) unless otherwise agreed with the client. - [https://browserstack.com](https://www.browserstack.com/)
- [ ]   Design files have been compared to staging site for accuracy.



# SEO 🤖

- [ ]   Robots.txt is set to prevent crawling on staging, allow on live site.
- [ ]   A sitemap has been set up.
- [ ]   301 Redirects are in place.
- [ ]   URL Structure is consistent.



# Assets: 🖼

- [ ]  Images use srcset with appropriate sizes.
- [ ]  Images and Iframes are lazyloaded - [https://github.com/aFarkas/lazysizes](https://github.com/aFarkas/lazysizes).
- [ ]  Images are served efficiently - Cloudinary/Imager
- [ ]  Images are served through a CDN if possible.
- [ ]  Images have alt tags.
- [ ]  A websafe font has been matched to help reduce FLOUT - [https://meowni.ca/font-style-matcher/](https://meowni.ca/font-style-matcher/)
- [ ]   Comments are removed for production



# Deployment: 📦

- [ ]   Develop and Master branches have auto-deploy hooks to staging and live.
- [ ]   Build for production runs on deploy
- [ ]   There is 48 hours before launch if DNS changes are required  (consider dropping TTL)
  


# Performance: ️⚡

- [ ]   Site has been tested with GTMetrix and Lighthouse.
- [ ]   Site has been tested on fast 3g conditions.
- [ ]   Scripts and stylesheets are minified as part of the build process
- [ ]   Critical styles are extracted and inlined. [https://github.com/filamentgroup/loadCSS](https://github.com/filamentgroup/loadCSS)
 
 

# Access 🤘

- [ ]   Content has a logical tabindex.
- [ ]   A ‘Skip to main content’ link is in place.
- [ ]   There is sufficient contrast between background and foreground colours/
- [ ]   Focus styles have been tested.
- [ ]   Site has been tested without a mouse.



# If you only check one thing 🔥
- [ ]  I'm not launching on a Friday.



# Also check these:
[https://frontendchecklist.io/](https://frontendchecklist.io/)  
[https://github.com/drublic/checklist](https://github.com/drublic/checklist)
[https://boxhead.io/launch-checklist/](https://boxhead.io/launch-checklist/)
