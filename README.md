# Square Game

A fun interactive game where three shapes—square, diamond, and circle—respond to hover effects. The project showcases basic HTML and CSS, utilizing modern layout techniques such as Flexbox to center the shapes on the page. Each shape changes color when hovered over, providing a playful and dynamic experience.

## Features

- **Hover Effects**: Shapes change their colors when hovered over:
  - **Square** turns red
  - **Diamond** turns green
  - **Circle** turns blue
- **Responsive Layout**: The shapes are centered both vertically and horizontally using Flexbox.

## Technologies Used

- **HTML5**: The structure of the page, including the shapes and layout.
- **CSS3**: The styling of the shapes, including hover effects and positioning.

## Structure

- `index.html`: The HTML structure containing the div elements for each shape.
- `style.css`: The CSS file used to style the shapes and their hover effects.

### HTML Breakdown

- The `#main` div centers all the shapes using Flexbox.
- Inside the `box` div, there are three shapes:
  - **Square** (`#square`)
  - **Diamond** (`#diamond`)
  - **Circle** (`#circle`)
  
Each shape has a specific hover effect:
- The square turns red.
- The diamond rotates and turns green.
- The circle turns blue.

### CSS Breakdown

- Flexbox is used to center the shapes in the `#main` container.
- The `.shapes` class is applied to all shapes for a consistent styling and alignment.
- Specific styles are applied to each shape, such as rotation for the diamond and border-radius for the circle.

## How to Run

1. Clone or download the repository.
2. Open `index.html` in your browser to see the interactive shapes.

## Inspiration

This project was inspired by the idea that learning and experimenting with CSS and HTML can be both fun and rewarding. As you hover over the shapes, remember: Every design can be simple, yet engaging!

## License

This project is open source and available under the [MIT License](LICENSE).
