# video-editor-pro

Video editor automation

### Steps

1. **Clone this Repository:**

   ```bash
   git clone https://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@github.com/wahdalo/video-editor-pro.git
   ```
   ```bash
   cd video-editor-pro
   ```
2. **Install Dependencies:**

   ```bash
   npm install
   ```
   
3. **Copy Youtube Cookies:**

   - Login to new account youtube.
   - Use the ["Export cookies JSON file for Puppeteer"](https://chromewebstore.google.com/detail/copy-cookies/jcbpglbplpblnagieibnemmkiamekcdg?utm_source=ext_app_menu) extension to copy your cookies.
   - Paste the cookies you have copied into the /data/cookies.json file

4. **Change the URL Target:**

   - Edit the url.txt file with several Youtube shorts links, separating each url with a newline

5. **Run the Script:**

   ```bash
   node index.js
   ```
