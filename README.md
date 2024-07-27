# video-editor-pro

Video editor automation

### Steps

1. **Clone this Repository:**

   ```bash
   git clone https://github.com/wahdalo/video-editor-pro.git
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
   - Use the ["Copy cookies"](https://chromewebstore.google.com/detail/copy-cookies/jcbpglbplpblnagieibnemmkiamekcdg?utm_source=ext_app_menu) extension to copy your cookies.
   - Paste the cookies you have copied into the /data/cookies.json file

4. **Change the URL Target:**

   - Edit the url.txt file with several Youtube shorts links, separating each url with a newline

5. **Run the Script:**

   ```bash
   node index.js
   ```
