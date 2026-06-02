# Hayat Foundation 🩸

> One drop. One life. One promise.

A blood donation platform connecting voluntary donors with patients in need across Pakistan.

## 🚀 Live Site

Hosted on GitHub Pages: `https://<your-username>.github.io/hayat-foundation`

## 📁 Structure

```
hayat-foundation/
└── index.html      ← entire website (HTML + CSS + JS in one file)
└── README.md       ← this file
```

## 🛠️ How to Host on GitHub Pages

1. Create a new GitHub repository named `hayat-foundation`
2. Upload both files (`index.html` and `README.md`)
3. Go to **Settings → Pages**
4. Under **Source**, select **Deploy from a branch**
5. Choose branch: `main`, folder: `/ (root)`
6. Click **Save** — your site will be live in ~1 minute!

## ℹ️ Notes

- All data (donors, requests) is stored in the **browser's localStorage** — no server or database needed.
- The admin panel password is set in the JavaScript (`ADMIN_PASS` variable).
- Data is per-device; it does not sync across browsers.
