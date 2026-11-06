## My First Website

A simple, static clothing-store website built with HTML and CSS. The page presents clothing categories, product details, promotions, and contact information using locally stored image assets.

## Features

- Store header with logo and navigation links
- New arrivals section
- Men's, women's, and kids' clothing sections
- Promotions section with discounted products
- Contact details and opening hours
- Responsive viewport configuration for browser and mobile display
- No external frameworks, dependencies, or build tools

## Project structure

```text
.
├── .html          # Main storefront page
├── README.md
├── logo.png       # Store logo
├── mainpic.png    # Main banner image
├── hoodie.png
├── denim.png
├── tshirt.png
├── dress.jpg
├── top.jpg
├── kids-tshirt.png
├── cuteshorts.png
├── socks.jpg
└── batik.png
```

The `.html` file is the website entry point. It contains the page markup and its styles in one file.

## Run locally

Because this is a static website, no installation is required.

1. Clone or download the repository.
2. Open `.html` in a web browser.

Alternatively, start a local server from the project directory:

```bash
python -m http.server 8000
```

Then visit [http://localhost:8000/.html](http://localhost:8000/.html).

## Product categories

The page currently includes:

- **New Arrivals:** Puma hoodie and Nike shoes
- **Men's Wear:** T-shirt and jeans
- **Women's Wear:** Dress and long-sleeve top
- **Kids Wear:** Barbie T-shirt and shorts
- **Promotions:** Socks and batik dress

Product names, prices, descriptions, availability, and contact information can be edited directly in `.html`.

## Customization

- Update the CSS in the `<style>` block to change colors, spacing, typography, and layout.
- Replace the image files while keeping their filenames to update the displayed products.
- Edit the navigation labels and section content in the HTML body.

## License

No license is currently specified for this project."
"# my-first-website" 
