# Vue UI Framework Tests

## Description
The objective of this project is to create a product page for a web shop in order to compare and analyze various trending UI frameworks. 

All of the implementations must be fully responsive (mobile-first) and have the following components:

* Top bar
  - Phone number with icon (left)
  - Shipping fees with icon (middle)
  - Return policy with icon (right)
* Navbar (sticky)
  - Logo
  - Hamburger menu button (mobile)
    - Same structure as the main menu
    - Full screen menu with sub-page navigation
  - Search button / box
  - Favorite products button
  - Cart button
  - User button
* Main menu (desktop)
  - All products
    - Mega menu on hover
    - Sub-categories with sub-links
  - Rooms
  - Style
  - Reviews
  - FAQ
* Product name and share icons (desktop)
  - Share icons
    - Page link
    - Facebook
    - Messenger
    - Viber
    - Email
    - SMS
    - Pinterest
    - WhatsApp
* Product pictures carousel
  - Most images are square (1:1)
  - Some images may be rectangular (16:9) or in other aspect ratios
  - Includes an embedded YouTube/Vimeo video player
  - Includes an embedded Sketchfab.com 3D player
  - The carousel itself must be rectangular (16:9)
  - A zoom button opens a full-screen gallery at the selected index with the same slides
  - Has left and right navigation arrows
  - Has dots below the carousel to indicate the current slide
  - Lazy loads images 
* Product details
  - Could be a column next to the carousel or a hovering box on top
  - On mobile, it comes after the carousel
  - Product name (mobile only)
  - Crossed-off regular price (in case of a discounted product)
  - Current price (with a superscript indicating VAT inclusive)
  - A highlighted box indicating how much the customer saves
  - Crossed-off recommended retail price
  - Financing option indicating installments per month with a more info icon (a modal opens on click)
  - Add to cart button
  - A bold text indicating the item is available or out of stock
  - Delivery dates (order now to receive it between a given date interval)
* Product variants
  - Small thumbnails with links to product variants
  - A slightly larger image is displayed on hover
* Purchase information
  - First row
    - Free delivery on orders above a certain price - with icon
    - Return policy - with icon
    - Customer rating and reviews via Repuso (carousel)
  - Second row
    - Why are our prices great
    - Why we chose this product to be in our catalog
* Product information
  - Table with vertical rows and grouped by sections
  - Features and dimensions
    - Product size
      - Length
      - Width
      - Height
    - Weight
  - Sizes
    - Lying surface size
    - Feet height
    - Other sizes
  - Product information
    - Material
    - Composition
    - Color
    - Frame material
    - Foot surface
    - Mounting
    - Other information
  - Maintenance (paragraph)
* Style description
  - Left column
    - Style photo
  - Right column
    - Style description paragraph
* Related products
  - A grid-style list of related products 
  - Medium thumbnail
  - Product name
  - Price
  - Add to cart button
* Newsletter subscription box
  - Left column
    - Contains a photo
  - Right column
    - An email address input box with a subscribe button
    - Information about the newsletter
* Footer links
  - Four vertical columns with a heading and links
  - First column (Before ordering)
    - FAQ
    - Gift vouchers
    - Data protection
    - General terms and conditions
    - Loan information
  - Second column (Customer service)
    - Live chat
    - Contact us
    - My orders
    - Return a product
    - My account
  - Third column (Meet us)
    - Business program
    - Magazine / blog
    - Our story
    - How are we different
    - Career
  - Fourth column (Follow us)
    - Facebook icon with link and # of likes
    - Instagram icon with link and # of followers
    - Pinterest icon with link
* Footer
  - Three side-by-side columns
  - First column
    - Made with <3
    - Impressum
  - Second column
    - All prices are VAT inclusive
  - Third column
    - Logos
      - MasterCard
      - VISA
      - American Express
      - Paypal
      - dpd
      - MPL

## App Structure

This project uses the instant prototyping feature of Vue.js.

The root directory contains a `package.json` file with the necessary dependencies.

It requires Vue CLI to be installed globally:

```shell script
yarn global add @vue/cli @vue/cli-service-global
```

Each UI framework has its own folder with an `App.vue` file that contains the product page implementation.

To run each test, run the following command inside the UI framework's folder:

```shell script
vue serve
```    

The common assets such as images, logos, and fonts are located in the `assets` folder.
  
## UI Frameworks

* [Bulma](https://bulma.io/)
* [Quasar](https://quasar.dev/)
* [Tailwind](https://tailwindcss.com/)
* [Lightning Design System](https://www.lightningdesignsystem.com/)
* [Elastic UI](https://elastic.github.io/eui/)
* [Element](https://element.eleme.io/)
* [AT UI](https://at-ui.github.io/)
* [Spectre.css](https://picturepan2.github.io/spectre/index.html)
* [Bootstrap Vue](https://bootstrap-vue.js.org/)
* [Ant Design Vue](https://www.antdv.com/)
* [Semantic UI](https://semantic-ui.com/)
* [Foundation](https://foundation.zurb.com/)
* [UIkit](https://getuikit.com/)
* [StorefrontUI](https://www.storefrontui.io/)
* [iView UI](https://www.iviewui.com/)

## Third-party Tools

* Carousels
  - [Owl Carousel](https://owlcarousel2.github.io/OwlCarousel2/)
  - [Mighty Slider](https://www.mightyslider.com/)
  
* Image galleries (full screen)
  - [Photo Swipe](https://photoswipe.com/)
  
* Share icons
  - [AddToAny](https://addtoany.com/)
  
* Animations
  - [Animate.css](https://daneden.github.io/animate.css/)