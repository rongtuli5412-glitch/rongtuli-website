RONG-TULI FINAL WEBSITE — বাংলা গাইড

১) index.html = মূল website
২) content.json = brand/contact/portfolio data
৩) assets/uploads/ = portfolio images
৪) admin/ = Decap CMS dashboard

OFFLINE TEST:
Double-click index.html. Browser security may prevent loading content.json locally; online Netlify version works normally.

FREE PUBLISH:
Netlify Drop-এ folder upload করে site live করা যায়। Default URL হবে your-project-name.netlify.app.

IMPORTANT CMS SETUP:
Decap CMS-এর /admin/ dashboard দিয়ে image upload/edit করতে হলে site-টি GitHub/GitLab repository-র সঙ্গে Netlify-তে connect করতে হবে, তারপর Netlify Identity এবং Git Gateway enable করতে হবে। CMS changes repository-তে save করে Netlify redeploy করবে।

NETLIFY STEPS:
1. GitHub-এ নতুন repository বানান: rongtuli-website
2. এই folder-এর সব file repository-তে upload করুন।
3. Netlify → Add new project → Import an existing project → GitHub → repository select → Deploy.
4. Site live হলে Domain management থেকে default netlify.app address দেখুন/rename করুন।
5. Identity enable করুন → Registration preference Invite only রাখুন।
6. Services → Git Gateway → Enable.
7. Identity → Invite users → নিজের email invite করুন → email verify করুন।
8. https://YOUR-SITE.netlify.app/admin/ খুলুন → login → Portfolio → image upload → Publish.

BOOKING:
Booking form WhatsApp-এ formatted request পাঠায়। Automatic booking confirmation করে না।

GOOGLE:
Google Search Console-এ site property add করে URL Inspection থেকে homepage indexing request করুন। Google result-এ আসার সময় নির্দিষ্ট নয়।
