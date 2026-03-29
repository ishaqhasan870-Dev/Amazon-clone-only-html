# 🛒 ShopNow — Amazon-Style E-Commerce Website

A fully functional, modern e-commerce platform inspired by Amazon's layout and UX.

## 🚀 Quick Start

**No installation required!** Just open `index.html` in any modern browser.

```bash
# Option 1: Direct open
Double-click index.html

# Option 2: Local server (recommended for full features)
cd shopify-clone
python3 -m http.server 8000
# Then visit: http://localhost:8000
```

## ✅ Features Implemented

### Pages
- 🏠 **Home Page** — Hero banner, categories grid, flash deals, AI recommendations
- 🛍️ **Shop / Product Listing** — Filterable, sortable product grid
- 📦 **Product Detail** — Image gallery, features, qty control, related products
- 🛒 **Cart** — Qty management, savings display, order summary
- 💳 **Checkout** — Address form, 4 payment methods (UPI/Card/COD/Net Banking)
- 👤 **Login / Signup** — Auth forms + Demo Login button
- 🙍 **Profile Page** — Tab nav: Profile info, orders, wishlist, addresses
- 📋 **Order History** — Full order cards with status
- ❤️ **Wishlist** — Save/remove products

### UI/UX
- ✅ Sticky navigation bar with search suggestions
- ✅ Category dropdown menu
- ✅ Amazon-inspired orange/black/white color theme
- ✅ Dark mode toggle (persists across sessions)
- ✅ Responsive design (mobile + desktop)
- ✅ Toast notifications for all actions
- ✅ Smooth hover animations & transitions
- ✅ Breadcrumb navigation
- ✅ Product badges (Deal / New / Hot)

### Features
- ✅ Add to cart / remove from cart
- ✅ Quantity management
- ✅ Price, rating, category filters
- ✅ Sort (popular, price asc/desc, rating, newest)
- ✅ Search with live suggestions
- ✅ User authentication (mock)
- ✅ Simulated checkout flow
- ✅ Wishlist with persistence
- ✅ AI-style recommendations (based on score = rating × log(reviews))
- ✅ Lazy loading images
- ✅ Pagination (12 products/page)
- ✅ LocalStorage persistence (cart, wishlist, orders, user, dark mode)

### Data
- ✅ **50 products** across 6 categories:
  - 📱 Electronics (10 items)
  - 👗 Fashion (8 items)
  - 🏡 Home & Kitchen (8 items)
  - 📚 Books (7 items)
  - ⚽ Sports (6 items)
  - 💄 Beauty (6 items)
  - + more

## 🏗️ Tech Stack
- Pure HTML5 + CSS3 + Vanilla JavaScript
- Google Fonts (Lexend + DM Mono)
- LocalStorage for data persistence
- No external dependencies — runs offline!

## 📁 File Structure
```
shopify-clone/
└── index.html    ← Complete app (single file, ~1200 lines)
```

## 🔑 Demo Login
Click **"🚀 Demo Login"** on the login page for instant access without filling forms.

## 📱 Mobile Support
Fully responsive — works on phones, tablets, and desktops.

## 🌙 Dark Mode
Click the **🌙 Dark** button in the navbar. Preference is saved.

---
*ShopNow is a simulated e-commerce demo. Not affiliated with Amazon.*
