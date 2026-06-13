# Punjab Land Records Portal

Government-style website for Mouza-wise Register Inventory.
Data is fetched live from Google Sheets.

---

## GitHub Pages Par Host Karne Ka Tarika

### Step 1 — GitHub Account
https://github.com par free account banayein

### Step 2 — New Repository
- "New repository" click karein
- Name: `land-records` (ya koi bhi naam)
- Public rakhen
- Create repository click karein

### Step 3 — Files Upload Karein
- "uploading an existing file" link click karein
- `index.html` ko drag & drop karein
- "Commit changes" click karein

### Step 4 — GitHub Pages Enable Karein
- Repository Settings mein jayein
- Left sidebar mein "Pages" click karein
- Source: "Deploy from a branch" select karein
- Branch: `main` → folder: `/ (root)`
- Save click karein

### Step 5 — Live Website
Kuch minutes mein aapki website live hogi at:
`https://YOUR-USERNAME.github.io/land-records/`

---

## Google Sheet Update Karna

Agar sheet ka URL badalna ho, `index.html` mein yeh line update karein:

```javascript
const SHEET_CSV_URL = 'YOUR_NEW_GOOGLE_SHEET_CSV_URL';
```

Sheet publish karne ka tarika:
1. Google Sheet open karein
2. File → Share → Publish to web
3. Format: CSV select karein
4. Publish click karein
5. URL copy karein

---

## Features
- Live Google Sheets data
- Mouza-wise grouped summary
- Click to expand year-wise details
- RHZ / Mutation / Shajra count per mouza
- Complete / In Progress status badges
- Jameel Noori / Noto Nastaliq Urdu font
- Search + filter by status and register type
- Fully responsive (mobile friendly)
- Professional government portal design
