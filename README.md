# Product Preview Card Component

## Project Description

This project is a responsive **Product Preview Card Component**, showcasing a product with key details such as the product image, title, description, price, and a call-to-action button to add it to the cart. The layout is optimized for both desktop and mobile devices, with a different product image displayed depending on the screen size.

The card's mobile version features a column layout, while the desktop version uses a row layout to enhance the user experience. The card adjusts seamlessly across different screen sizes using media queries.

## Features

- **Responsive Design**: Optimized for both mobile and desktop devices.
- **Dynamic Image Switching**: Displays a different image based on screen width.
- **Elegant Typography**: Incorporates two custom fonts from Google Fonts, `"Montserrat"` and `"Fraunces"`.
- **Call-to-Action**: A stylized 'Add to Cart' button with hover effects.
- **Pricing Details**: Shows the product price with a strikethrough for the previous price.

## Technologies Used

- **HTML5**: Structuring the content of the card.
- **CSS3**: Styling the card, including flexbox layout and responsive design.
  - Media Queries for mobile responsiveness.
  - Custom fonts from Google Fonts.
- **SVG Icons**: Used for the cart icon in the button.

## Installation & Setup

To run this project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/PDineshMurugan/product-preview-card.git

  ## Folder Structure
  |-- images/
|   |-- image-product-desktop.jpg   # Product image for desktop
|   |-- image-product-mobile.jpg    # Product image for mobile
|
|-- styles.css                      # Main CSS file for styling
|
|-- index.html                      # HTML file for the project
|
|-- README.md                       # Project's README file

## Responsive Design
# Desktop View
- Displays a large product image on the left and the product details on the right.
- Image dimensions: 500px x 500px with a border radius for rounded corners on the left.
# Mobile View
- Stacks the product image on top of the content.
- Image dimensions: 100% width and 400px height, adapting perfectly to smaller screens.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

# Acknowledgments
- Frontend Mentor for providing design inspiration for this project.
- Google Fonts for the custom fonts used in this project.
