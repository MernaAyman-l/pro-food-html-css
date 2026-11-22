# Food Lover — Restaurant Landing Page & Menu Showcase

A responsive restaurant website (`Food Lover`) built with semantic HTML5 and custom CSS3, featuring a full-screen hero header, restaurant history section, special offers showcase, two-column menu list, daytime meal schedule, food gallery, and contact details with a message form.

## Project Structure & Key Files
- `index.html`: Single-page restaurant layout structured across `<header>`, `<main>` (`#about`, `#offers`, `#menu`, `#daytime`, `#gallery`), `#contact`, and `<footer>`.
- `style.css`: Stylesheet covering layout containers (`max-width: 1100px`), color palette (`#e4b95b` gold accent, `#383848` dark slate, `#f4f4f4` light sections), flexbox sections, hover states, and media queries for tablet (`max-width: 1000px`) and mobile (`max-width: 600px`) screens.
- `images/`: Referenced visual assets including logo, hero/offer/daytime backgrounds, menu dish photos (`food1.png`–`food12.jpeg`), and gallery images (`gallery1.jpeg`–`gallery6.jpeg`).

## Page Sections & Features
- **Header & Hero Banner:** Navigation bar (`Home`, `About`, `Menu`, `Gallery`, `Contact`) with brand logo (`images/logo.png`), dark overlay hero section (`Welcome To Food Lover Restaurtant`), subtitle, and `Book a Table` CTA button over `images/home_bg.jpeg`.
- **About Section (`#about`):** Restaurant story (`More Than 25+ years of Experiance`), two descriptive paragraphs, `LEARN MORE` button, and feature image (`images/about_img.png`).
- **Special Offers (`#offers`):** Three-item promotional grid (`Quattro Pasta`, `Vegertarian Pasta`, `Gluten-Free Pasta`) showing strikethrough original prices (`$55.00`) alongside highlighted offer prices (`$18.00`).
- **Special Menu (`#menu`):** Two-column layout (`menu-items-left` and `menu-items-right`) with 12 dishes (`LASAL CHEESE`, `JUMBO CRAB SHRIMP`, `KOKTAIL JUCIE`, `CAPO STEAK`, `ORGANIC FRUIT SALAD`, `CHEESE PIZZA`, `KOFTA MEAT`, `SPANISH PIES`, `CHEESE TOST`, `FRUIT SALAD`, `CHICKEN SHAWARMA`, `MEGA CHEESE PIZZA`), prices, descriptions, and an `EXPLORE FULL MENU` button.
- **Daytime Schedule (`#daytime`):** Four meal-time blocks (`Breakfast`, `Lunch`, `Dinner`, `Dessert`) with icons and time windows over a fixed background (`images/daytime_bg.jpeg`).
- **Food Gallery (`#gallery`):** Responsive wrapping gallery displaying six dish photos (`gallery1.jpeg` to `gallery6.jpeg`) with hover opacity transitions.
- **Contact & Footer (`#contact`, `#footer`):** Address (`El Tahrir Street – Dokki`), phone, email, weekday/weekend working hours, social links (Font Awesome 6.7.2 icons), contact form (`Full Name`, `Email Address`, `Subject`, `Message`, `SEND MESSAGE`), and footer credit.

## Built With
- **HTML5**
- **CSS3** (`style.css`, Flexbox & Media Queries)
- **Icons:** Font Awesome (`6.7.2` via CDN)

## How to Run
1. Place `index.html` and `style.css` alongside the `images/` folder containing the referenced image files.
2. Open `index.html` in any web browser (or run via a local development server such as VS Code **Live Server**).
