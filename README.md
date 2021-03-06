# Link with Women

A chrome extension to help you connect with more women on LinkedIn:

-Navigate to the My Network tab (on LinkedIn)<br/>
-Click the Link with Women Chrome Extension icon<br/>
-The extension will filter people currently loaded

If you want to use this extension, see the install instructions listed below.

# Demo

![LinkWithWomen](/readme/Demo.gif?raw=true "My Network")

# Presentation

[![Women in Tech Presentation](/readme/Presentation.jpg)](https://slides.com/ruthnaebeck/linkwithwomen/)

# Press
07/20/2017 - Forbes.com - [How Capital One Supports Diversity From Top To Bottom](https://www.forbes.com/sites/gaudianohunt/2017/07/20/how-capital-one-supports-diversity-from-top-to-bottom)

# Install Instructions

Sign-up for a FREE API key from Clarifai:<br/>
https://developer.clarifai.com/signup/

Sign-up for a FREE API key from Gender-API:<br/>
https://gender-api.com/en/account

```
git clone the repo
cd wit
touch secret.js
```

Add the following to secret.js (replace words with actual keys and secret from sign-up step):

```
const clarKey = 'CLARIFAI_ID_HERE'
const clarSecret = 'CLARIFAI_SECRET_HERE'
const genderKey = 'GENDER_API_KEY_HERE'
```

In Chrome, navigate to:  chrome://extensions/<br/>
Check the Developer mode check box<br/>
Click Load unpacked extension...<br/>
Select the wit folder<br/>

# Resources

https://developer.chrome.com/extensions<br/>
https://www.clarifai.com/<br/>
https://gender-api.com/<br/>
