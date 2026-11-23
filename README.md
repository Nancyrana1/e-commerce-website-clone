# Amazon Clone – Frontend Practice Project

A static, Amazon-inspired e-commerce homepage created as my first hands-on frontend project. I built it for educational purposes to practise structuring a webpage with HTML and styling a familiar e-commerce layout with CSS.

This project helped me understand how the different sections of an online shopping homepage fit together, from the navigation bar to promotional product cards and the footer.

## Project Overview

The page recreates selected visual elements of an Amazon-style shopping homepage, including:

- A top navigation bar with a logo, delivery location, search area, account links, returns, and cart.
- A secondary navigation panel with shopping links and a deals message.
- A hero banner with a promotional message.
- Product/category cards arranged in two rows.
- A multi-column footer with informational links.
- Interface icons loaded through Font Awesome.

## Built With

- **HTML5** – page structure and content.
- **CSS3** – layout, spacing, colors, typography, and hover styling.
- **Font Awesome 6** – interface icons loaded through its CDN.

## Repository Files

```text
e-commerce-website-clone/
├── README.md
├── ecommerce.html
└── ecommerce.css
```

The HTML and CSS refer to local image files for the logo, hero banner, and product cards. Those image assets are not currently included in the repository, so add the required images to the project folder for the page to display as intended.

## Run Locally

1. Clone this repository:

   ```bash
   git clone https://github.com/Nancyrana1/e-commerce-website-clone.git
   ```

2. Open the project folder:

   ```bash
   cd e-commerce-website-clone
   ```

3. **Check the stylesheet link before previewing:** the current HTML references `dropbydrop.css`, but the stylesheet in this repository is named `ecommerce.css`. Update the stylesheet link in the `<head>` of `ecommerce.html` to `ecommerce.css`.

4. Add the image assets referenced in the HTML/CSS to the project folder.

5. Open `ecommerce.html` in your browser, or use a local development extension such as Live Server.

## What I Learned

Building this project gave me practical experience with:

- Creating a webpage using HTML elements.
- Styling navigation bars, banners, cards, and footers with CSS.
- Using Flexbox to arrange content.
- Working with background images and an external icon library.
- Applying hover effects and consistent spacing.
- Breaking a larger page into smaller sections.

As my first frontend practice project, this was an important step in building confidence and understanding how an e-commerce interface can be put together.

## Future Improvements

As I continue learning, I would like to:

- Make the layout responsive across mobile, tablet, and desktop screens.
- Add working search and category filtering.
- Add product detail views and shopping-cart interactions.
- Improve accessibility and keyboard navigation.
- Build additional pages and explore backend integration.

## Disclaimer

This project is an independent educational exercise inspired by the visual layout of Amazon. It is not affiliated with, endorsed by, or connected to Amazon. Amazon and related brand assets are the property of their respective owners.

## Author

Created by [Nancyrana1](https://github.com/Nancyrana1) as a learning project while exploring frontend web development.

Suggestions and constructive feedback are welcome!
