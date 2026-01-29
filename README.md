# PureMuga

A static showcase website presenting authentic Assamese silk products and traditional wear for the Jorhat branch of Assam Sambabay Resham Prathisthan Ltd.

---

## 1. Project Title & Short Description

PureMuga is a business showcase website focused on Assamese silk heritage and traditional textiles.  
It highlights the collections and services of the Jorhat store of Assam Sambabay Resham Prathisthan Ltd., with an emphasis on in-person visits and physical product experience.

---

## 2. Overview

PureMuga is an informational, static website designed to:

- Present authentic Assamese silk products and traditional garments in a structured, visually refined manner  
- Communicate the store’s identity, values, and heritage to prospective customers  
- Provide clear information about location, hours, and ways to contact the Jorhat store  

The website follows a **physical-store-first** approach:

- It encourages customers to visit the showroom in Jorhat, Assam, to see, feel, and purchase products  
- All calls-to-action are oriented towards in-store visits and direct contact  

It is **not** an e-commerce platform:

- No online ordering  
- No payments or checkout  
- No shipping or delivery workflows  

---

## 3. Key Features

- **Heritage-Inspired UI**  
	Carefully selected typography, colors, and layout evoke the elegance of Assamese silk and traditional motifs.

- **Product Galleries**  
	Category-based sections showcasing key product types with curated images and descriptive text.

- **Informational Focus**  
	Clear, text-first content explaining silk varieties, garment types, and store offerings.

- **Responsive Design**  
	Layouts optimized for desktop, tablet, and mobile using modern CSS techniques.

- **Static & Fast**  
	Pure HTML, CSS, and vanilla JavaScript delivered as static assets for fast load times and simple hosting.

- **Store Location, Hours, and Contact**  
	Dedicated sections for address, opening hours, contact details, and an embedded map for the Jorhat branch.

---

## 4. Pages Breakdown

### Home

- Introduction to PureMuga and the Jorhat store  
- High-level overview of key collections  
- Brief statements on authenticity, quality, and heritage  
- Prominent call-to-action encouraging customers to visit the store  

### Products

- Product categories listed with images and descriptions  
- Visual galleries for major garment types  
- Clear indication that items shown are representative and available in-store  

### About Us

- Background of Assam Sambabay Resham Prathisthan Ltd. and its Jorhat branch  
- Short explanations of Assamese silk varieties (Muga, Pat, Eri, etc.)  
- Emphasis on authenticity, craft, and long-standing trust  
- Reasons to visit the physical showroom  

### Contact

- Full postal address of the Jorhat store  
- Store hours and weekly availability  
- Phone and email contact details  
- Embedded map for location guidance  
- Clear guidance to contact or visit for enquiries and purchases  

---

## 5. Product Categories Displayed

The website showcases, at a category level, products such as:

- **Pure Muga Mekhela Chador**  
- **Pat Silk Mekhela Chador**  
- **Mekhela Chador with Riha**  
- **Tas Pat Mekhela Chador**  
- **Pat & Tas Sarees**  
- **Jora Sets & Traditional Assamese Wear**  

These categories are visual and descriptive only; they are intended to represent the range available at the Jorhat store.

---

## 6. Technology Stack

- **HTML5** – Semantic markup and accessible document structure  
- **CSS3** – Custom styling, responsive layouts with flexbox and grid  
- **Vanilla JavaScript** – Light enhancements such as image handling or minor UI behavior  
- **No Backend / Database** – Entirely static; no server-side processing, frameworks, or databases  

---

## 7. Project Structure

A simplified view of the project layout:

```text
AssameseSilkShop/
├── index.html                # Home page
├── products.html             # Products showcase
├── about.html                # About the store and heritage
├── contact.html              # Contact and location
├── css/
│   └── style.css             # Main stylesheet
├── images/
│   ├── index/                # Homepage imagery
│   ├── about/                # About page imagery
│   ├── products/             # Product/category visuals
│   │   ├── sador-mekhela/
│   │   ├── silk-sarees/
│   │   └── traditional-garments/
│   └── gamusa.png            # Decorative / identity asset
└── README.md                 # Project documentation
```

The structure is intentionally simple to remain portable and static-hosting friendly.

---

## 8. Image & Content Disclaimer

- Product images are **representative** of the styles, weaves, and categories offered at the Jorhat store.  
- Actual inventory, colours, motifs, and availability may change over time.  
- Some sections may use **placeholder images** where final product photography is pending.  
- Descriptions are written to reflect real product types but should not be treated as a live catalogue or stock list.

For accurate and up-to-date product choices, customers should visit the physical store in Jorhat.

---

## 9. Important Notice

**This website does not support online sales or payments.**

- No shopping cart or checkout functionality  
- No online payment integration  
- No shipping, delivery, or order tracking  

All purchases, price confirmations, and detailed product selections are handled **only at the physical store in Jorhat, Assam**. Customers are invited to visit in person for a complete experience.

---

## 10. Local Development

This is a static website and can be viewed locally without any build step.

### Option 1: Open Directly in Browser

1. Download or clone the repository.  
2. Open `index.html` in any modern web browser.  

### Option 2: Use a Simple Local Server

Using Python 3:

```bash
cd AssameseSilkShop
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

Using Node.js (http-server):

```bash
cd AssameseSilkShop
npx http-server .
```

Using PHP:

```bash
cd AssameseSilkShop
php -S localhost:8000
```

---

## 11. Deployment

PureMuga is fully static and can be deployed to any static hosting provider, including:

- GitHub Pages  
- Netlify  
- Vercel  
- AWS S3 (optionally with CloudFront)  
- Firebase Hosting  
- Conventional shared or VPS hosting with a basic web server  

Deployment typically consists of uploading the HTML, CSS, JavaScript, and image assets to the hosting platform. No application server, database, or runtime environment is required.

---

## 12. Association & Credits

PureMuga represents the **Jorhat branch of Assam Sambabay Resham Prathisthan Ltd.**, a cooperative entity working to uphold and promote:

- Authentic Assamese silk traditions  
- The craftsmanship of local weavers  
- The cultural significance of Mekhela Chador, sarees, gamusa, and related textiles  

The website aims to reflect the organisation’s commitment to authenticity, heritage, and craftsmanship through a careful, respectful visual and content design.

---

## 13. License

This project is a **proprietary business website**.

All content, images, branding elements, and associated assets are the exclusive property of **Assam Sambabay Resham Prathisthan Ltd.** and are protected under applicable copyright and intellectual property laws.

Unauthorised copying, redistribution, or commercial reuse of any part of this website is not permitted without prior written consent from the organisation.
