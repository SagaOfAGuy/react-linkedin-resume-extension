# react-linkedin-resume-extension
Chrome extension that allows for users to scrape Linkedin Profile information and save it as a DOCX file.
Web Store Link: https://chromewebstore.google.com/detail/linkedin-profile-download/ebjdfpoegdaamleafgbedpimdgjlplja?authuser=0&hl=en

# Installation
1. Open Chrome browser
2. Browse to the URL `chrome://extensions` in the Chrome browser
3. Enable `Developer Mode` 

![alt text](image.png)

4. Download this chrome extension repo: 
```bash
git clone https://github.com/SagaOfAGuy/react-linkedin-resume-extension.git
```

5. Click the `Load Unpacked` button in the browser

![alt text](image-1.png)

6. Browse to the directory that has the chrome extension downloaded, and chose to import the `dist` folder and click on the `select` button

![alt text](image-2.png)

7. Confirm that the extension has been installed:

![alt text](image-3.png)

# Usage
To use the extension, we can follow these steps below: 

1. Browse to a Linkedin Profile page in the chrome browser

2. Click the `Download Profile DOCX` button to download the profile information

![alt text](image-4.png)


# Building the extension
1. To build this extension, we first need to download any dependency packages. To do this, we can run the command below to install needed packages: 
```bash
npm install 
```
2. We can build this extension from source code via the command below: 

```bash
npm run build
```
