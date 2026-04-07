# Eco-Friendly E-Commerce Platform

A static web-based eco-fashion and sustainable shopping project with category pages, cart flow, authentication pages, and checkout/order flow.

## Updated Project Structure

The project is now organized by file type:

```text
Eco Fashion Retailer-project/
├── index.html                 # Entry file (redirects to html/index.html)
├── html/                      # All page files
│   ├── index.html
│   ├── beauty.html
│   ├── clothing.html
│   ├── electronics.html
│   ├── food.html
│   ├── fashionacc.html
│   ├── cartpage.html
│   ├── login_page.html
│   ├── register.html
│   ├── place-order.html
│   ├── payment.html
│   ├── order-confirmation.html
│   └── invoice-preview.html
├── css/                       # Stylesheets
│   ├── styles1.css
│   ├── cartpage.css
│   ├── fashionacc.css
│   └── login_page.css
├── js/                        # JavaScript files
│   ├── main1.js
│   ├── cartpage.js
│   └── search.js
└── images/                    # Image assets
```

## Features

- Responsive UI with Bootstrap and custom CSS
- Product browsing by category (clothing, electronics, food, beauty, accessories)
- Search and product interactions
- Shopping cart with local storage persistence
- User authentication pages (login/register UI)
- Checkout flow: cart -> place order -> payment -> confirmation -> invoice preview

## How To Run

1. Clone or download this repository.
2. Keep all folders (`html`, `css`, `js`, `images`) in the same root directory.
3. Open root `index.html` in your browser.
   - It redirects to `html/index.html` (main page).

## Tech Stack

- HTML5
- CSS3
- JavaScript (ES6)
- Bootstrap 5
- Font Awesome
- Swiper.js
- Browser Local Storage API

## Notes

- Internal links and asset paths were updated for the new folder layout.
- If you add new pages, place them in `html/` and use relative paths:
  - CSS: `../css/<file>.css`
  - JS: `../js/<file>.js`
  - Images: `../images/<file>`