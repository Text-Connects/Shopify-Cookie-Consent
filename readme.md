#Shopify Cookie Consent Liquid Update  

Shopify Liquid Version of https://cookieconsent.insites.com/download/

1. Download All Files in Repo
2. Upload the cookieconsent.min.css and cookieconsent.min.js to the Shopify Theme Assets Folder
3. Create a new liquid file in the SNIPPETS folder called cookie-consent.liquid
4. Copy everything from the cookie-consent.liquid file in this REPO to the new file.
5. Open the Theme / CONFIG / Settings_schema.json File
6. Find the ] at the end of the file, immeadiately before this paste the entire contents of the settings-schema-update.liquid file
7. Save all Files
8. Open your theme.liquid file and paste the following code right before the </body> tag

     {% include 'cookie-consent' %}


10. Click CUSTOMIZE THEME and go to Theme Settings / Cookie Consent
11. Update all setting.
12. Test your settings and publish new theme.