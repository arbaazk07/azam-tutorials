# Azam Tutorials — Project Resources

Live site: https://azam-tutorials.vercel.app

---

## 🔗 Important Links

| Resource | URL |
|---|---|
| Vercel Dashboard | https://vercel.com/arbaazk07s-projects/azam-tutorials |
| Formspree – Admission Form | https://formspree.io/f/xzdkpdro |
| Formspree – Contact/Enquiry Form | https://formspree.io/f/mojpajdz |
| Google Sheet (Submissions) | https://docs.google.com/spreadsheets/d/1di0OHhBRKAn6clwEa8ywBB8GjQFl7ng_JwM52qZrEibJTSLb0W5L68pC/edit |
| Apps Script (Web App) | https://script.google.com/macros/s/AKfycbwlwOSVTJ6ABo9l9qycIX2lI8Yukfjzj1rtpV-2iCpY6M3pWwMNSR2Q-5HQUUbXPmQd/exec |

---

## 📧 Contact Details

| Field | Value |
|---|---|
| Email | azamtutorials01@gmail.com |
| Phone | +91 81068 44642 |
| Address | 11-3-106 New Mallepally, Hyderabad – 500024 |

---

## ⚙️ How Everything Works

### Form Submissions
When a user submits either form on the website:
1. **Formspree** sends an email to `azamtutorials01@gmail.com`
2. **Google Apps Script** logs a new row in the Google Sheet

### Google Sheet Tabs
- **Admissions** — logs every admission form submission
- **Enquiries** — logs every contact/enquiry form submission

### Vercel Analytics
- Enabled on Hobby plan (free)
- Tracks pageviews and Web Vitals
- Script already included in `index.html`

---

## 🛠️ How to Update the Site

1. Edit `index.html` locally
2. Push to `main` branch on GitHub
3. Vercel auto-deploys in ~10 seconds

---

## 📁 Repo Structure

```
/
├── index.html       # Main website (single file)
└── README.md        # This file
```

---

## 🔄 If You Need to Re-deploy Apps Script

1. Go to Google Sheet → Extensions → Apps Script
2. Make changes if needed
3. Deploy → New deployment → Web app → Anyone → Deploy
4. Copy new URL and update `index.html` (search for `SHEETS_URL`)

---

## 📌 Formspree Free Tier Limits
50 submissions/month per form
If you exceed this, upgrade or switch to Apps Script only

- 50 submissions/month per form
- If you exceed this, upgrade or switch to Apps Script only
