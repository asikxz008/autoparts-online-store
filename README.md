# AutoParts Online Store

A five-page responsive automotive parts website based on the supplied Figma design and midterm requirements.

## Pages

- `index.html` — Home
- `products.html` — Products, working category/price filters, product selection, an email order form, and the required table
- `categories.html` — Categories
- `about.html` — About Us
- `contact.html` — Contact, including the required email form

## Technologies

Semantic HTML5, CSS3, and a local copy of Bootstrap 5.3.8 CSS. Layouts use Bootstrap grid and utilities, Flexbox, CSS Grid, positioning, and mobile/tablet media queries. Photos were generated for this project and icons come from the supplied Figma design. There is no JavaScript.

## Open or publish

Published site: https://mikosh001.github.io/autoparts-online-store/

Open `index.html` in a browser. On the Products page, radio controls filter the seven products and checkboxes add products to the same-page cart. The order and contact forms open the visitor's email application addressed to supportautopartsstore@gmail.com. Product details and prices are sample project content. The cart is limited to the Products page because the site uses only HTML, CSS, and Bootstrap.

Store phone: +77757478601. Phone links open the visitor's calling application. Footer social links open the Facebook and Instagram home pages.

## Team source files

- Member 1: Home, Categories, header navigation, shared product-card appearance; `css/home.css`, `css/categories.css`.
- Member 2: Products, category/price filtering, selection, same-page cart and comparison table; `css/catalog.css`, `css/selection.css`, `css/cart.css`.
- Member 3: About, Contact, common base/footer styles and stylesheet integration; `css/base-footer.css`, `css/about-contact.css`, `style.css`.

Each member checks and commits their assigned files using their own Git account. Merge member 1 and member 2 before member 3, whose `style.css` imports all seven CSS files. Bootstrap and image assets stay in their existing folders.
