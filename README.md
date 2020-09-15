# Google-conversion-for-Opencart-3
The modifier is in beta, and will be updated and improved
The idea is to work on all three, regardless of who knows it.
Installation step by step:
1. Make a backup of the database and site files!
2. Extract install.xml from the archive and make the following changes:
3. On line 118, replace {{YOUR_THEME_NAME}} with the name of your topic
4. On line 133, replace {{YOUR_GTM_ID}} with your Google Tag Manager ID
5. If your topic contains the file common / success.twig On line 72, replace the default with the name of your topic
6. Pack back and install
7. After installation, update the modifiers
8. Check the functionality using the Tag Manager Validator extension in preview mode
