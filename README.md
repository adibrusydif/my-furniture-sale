# 🛋️ Furniture for Sale

A simple website to list your furniture for sale. Images and data are stored in this GitHub repository.

## 🚀 Setup (5 minutes)

### 1. Create the GitHub repo

1. Go to [github.com/new](https://github.com/new)
2. Name it something like `my-furniture-sale`
3. Set it to **Public**
4. Click **Create repository**

### 2. Upload these files

Upload the two files to your repo:
- `index.html` → public gallery
- `admin.html` → admin panel

You can drag & drop them directly on GitHub.

### 3. Enable GitHub Pages

1. Go to your repo → **Settings** → **Pages**
2. Under **Source**, select `Deploy from a branch`
3. Choose branch: `main`, folder: `/ (root)`
4. Click **Save**

Your site will be live at:
```
https://YOUR_USERNAME.github.io/my-furniture-sale
```

### 4. Get a GitHub Token (for admin)

1. Go to **GitHub → Settings → Developer Settings → Personal Access Tokens → Fine-grained tokens**
2. Click **Generate new token**
3. Set name: `Furniture Sale Admin`
4. Under **Repository access** → select your repo
5. Under **Permissions** → **Contents** → set to **Read and Write**
6. Click **Generate token** and copy it

### 5. Configure Admin Panel

1. Open `https://YOUR_USERNAME.github.io/my-furniture-sale/admin.html`
2. Fill in:
   - GitHub Username
   - Repository Name (`my-furniture-sale`)
   - Personal Access Token
3. Click **Save & Connect**
4. Start adding products! 🎉

## 📱 Features

### Public Gallery (`index.html`)
- Responsive grid (mobile-first)
- Image slideshow per product
- Filter: All / Available / Sold
- **SOLD** badge overlay

### Admin Panel (`admin.html`)
- Add products with multiple images
- Edit any product
- Mark as Sold / Available
- Delete products
- Images uploaded directly to GitHub

## 📁 Repo Structure (auto-created)

```
my-furniture-sale/
├── index.html
├── admin.html
├── README.md
├── data/
│   └── products.json    ← auto-created on first product
└── images/
    └── ...              ← uploaded via admin panel
```

## 🔗 Share with friends

Just send them your GitHub Pages URL:
```
https://YOUR_USERNAME.github.io/my-furniture-sale
```
