What this is
An online furniture store website template built with vanilla HTML, CSS, and JavaScript. It showcases a furniture e-commerce storefront with product catalog, team introduction, customer testimonials, and contact information. The template is live at https://frosty-brahmagupta-37bb35.netlify.app.

Stack
Language(s): HTML, CSS, JavaScript
Framework / runtime: Bootstrap 4.5.2, jQuery 3.5.1
Notable libraries: Slick Carousel (image slider), Magnific Popup (image lightbox), Font Awesome (icons), Google Fonts
How it's organized
Code
index.html          Main single-page entry point
css/
  Style.css         Global styling with custom CSS variables, layout, components
js/
  main.js           Slider initialization and image popup functionality
assets/             Product images, testimonial photos, promotional banner images
favicon.png         Site icon
How it fits together: The site is a static single-page application centered on index.html. Bootstrap provides responsive grid layout and components (navbar, dropdowns). The page is divided into sections (home banner via Slick carousel, about us with embedded video, product grid, team profiles, testimonials, footer). JavaScript in main.js initializes the image slider and adds lightbox functionality to product images. Styling is handled by Style.css which defines custom CSS variables (colors, fonts) and component-specific styles that layer on top of Bootstrap's base styles.

How to run it
The site is static HTML and requires no build step. Open index.html in a browser or serve via any HTTP server:

bash
# Option 1: Direct file open
open index.html

# Option 2: Simple Python server
python3 -m http.server 8000
# then visit http://localhost:8000

# Option 3: Using Node's http-server (if installed)
npx http-server
