
Cameroonian Consortium in Denmark (CCD) - Static Website Package
---------------------------------------------------------------

Files included:
 - index.html      : Main website file
 - styles.css      : Styling (Cameroon + Denmark color theme)
 - assets/logo.svg : Placeholder CCD logo
 - assets/hero.jpg : Placeholder hero image

Contact form:
 - The contact form posts to https://formsubmit.co/info@cameroonianconsortium.dk
   This will forward form submissions to info@cameroonianconsortium.dk via FormSubmit service.
   If you prefer using One.com's built-in form handler, replace the form 'action' attribute in index.html 
   with your One.com form action URL or configure One.com's form settings after upload.

How to deploy on One.com:
1. Log in to One.com control panel -> File Manager
2. Upload the entire contents of this folder into /public_html/
3. Ensure index.html is in the root of your public_html
4. (Optional) For server-side form handling using One.com, update the form action as explained above.
5. Create email accounts in One.com control panel (e.g. info@cameroonianconsortium.dk)

Notes:
 - This is a static HTML site intended for simple hosting. If you later want dynamic blog management, consider installing WordPress and migrating content.
 - Replace placeholder images and update content where necessary.
