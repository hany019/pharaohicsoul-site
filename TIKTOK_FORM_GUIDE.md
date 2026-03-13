# TikTok Developer App Submission — Complete Guide for PharaohicSoul
## Everything you need to copy-paste to fix all 7 errors

---

## ERROR 1: App Icon ✅
Upload the file: `app-icon.png` (included in this package)
- It's 1024x1024px, PNG format

---

## ERROR 2: Description (max 120 characters)
Copy this EXACTLY into the Description field:

```
PharaohicSoul sells handmade Egyptian copper products and decor. We share product videos and content on TikTok.
```
(109 characters)

---

## ERROR 3: Terms of Service URL
After you deploy the website to GitHub Pages, your URL will be:

```
https://YOUR-GITHUB-USERNAME.github.io/pharaohicsoul-site/terms.html
```

---

## ERROR 4: Privacy Policy URL
```
https://YOUR-GITHUB-USERNAME.github.io/pharaohicsoul-site/privacy.html
```

---

## ERROR 5: Platforms
Check: ✅ Web

Then in the Web section, add your redirect URI:
```
https://YOUR-GITHUB-USERNAME.github.io/pharaohicsoul-site/
```

---

## ERROR 6: App Review — Explain how each product and scope works (max 1000 chars)
Copy this into the App Review text box:

```
PharaohicSoul is a handmade Egyptian copper and decor shop that sells on Etsy. We use the TikTok Content Posting API to publish product showcase videos and behind-the-scenes content directly to our TikTok account (@pharaohicsoul).

How it works:
1. We create product videos (copper coffee sets, Egyptian decor items) using our content management tool.
2. The Content Posting API allows us to upload and publish these videos to our TikTok profile.
3. We use the video.publish scope to post content directly to TikTok.
4. Users (our TikTok account owner) authorize the app and can preview content before publishing.
5. All content is original — showing our handmade products, craftsmanship process, and Egyptian artistry.

Scopes used:
- user.info.basic: To verify the connected TikTok account identity.
- video.publish: To upload and publish product videos to the authorized TikTok account.

No user data is collected or stored. The integration is used solely by the shop owner to post product content.
```
(889 characters)

---

## ERROR 7: Demo Video
You need to record a screen recording showing the integration flow.

### What TikTok wants to see in the video:
1. Your website (pharaohicsoul-site on GitHub Pages)
2. A user logging in / authorizing with TikTok (use Sandbox mode)
3. Selecting/creating content to post
4. The content being published to TikTok
5. The posted content visible on TikTok

### Since your app isn't built yet, use the SANDBOX:
1. Go to developers.tiktok.com
2. Switch to "Sandbox" tab (you can see it next to "Production" in your app)
3. In Sandbox, you can test the flow without a live app
4. Record your screen showing the Sandbox test

### Recording tips:
- Use QuickTime on Mac (File > New Screen Recording)
- Keep it under 50MB
- Show each step clearly
- 1-2 minutes is enough

---

## DEPLOYING YOUR WEBSITE (GitHub Pages — FREE)

### Step 1: Create GitHub Account (if you don't have one)
1. Go to github.com
2. Click "Sign up"
3. Use your email, create username, verify

### Step 2: Create Repository
1. Click the "+" button (top right) > "New repository"
2. Name it: `pharaohicsoul-site`
3. Make it: Public
4. Check "Add a README file"
5. Click "Create repository"

### Step 3: Upload the Website Files
1. In your new repository, click "Add file" > "Upload files"
2. Drag and drop ALL 3 files:
   - index.html
   - terms.html
   - privacy.html
3. Click "Commit changes"

### Step 4: Enable GitHub Pages
1. Go to repository "Settings"
2. In the left sidebar, click "Pages"
3. Under "Source", select "Deploy from a branch"
4. Branch: main, folder: / (root)
5. Click "Save"
6. Wait 2-3 minutes
7. Your site will be live at: https://YOUR-USERNAME.github.io/pharaohicsoul-site/

### Step 5: Verify URLs in TikTok
1. Go back to TikTok Developer Portal
2. Click "URL properties" (top right of your app page)
3. Add your GitHub Pages domain
4. Update Terms and Privacy URLs with your actual GitHub Pages URLs

---

## PRODUCTS & SCOPES TO SELECT IN TIKTOK

In the "Products" section at the bottom, click "+ Add products" and select:
- Content Posting API

In the "Scopes" section, select:
- user.info.basic
- video.publish

---

## AFTER APPROVAL

Once TikTok approves your app (usually 3-7 days), you'll have:
- Client Key: awaa4hkx9zcn75ke (you already have this)
- Client Secret: (you already have this)

Then we connect these to your Content Pharaoh agent and you're live! 🏺
