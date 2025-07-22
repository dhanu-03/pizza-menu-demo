# Fast React Pizza App

A demo pizza menu web application built with [Create React App](https://github.com/facebook/create-react-app).

## Features

- Displays a menu of authentic Italian pizzas
- Shows ingredients, price, and sold-out status for each pizza
- Responsive and modern UI with custom styles
- Dynamic open/close hours message in the footer

## Project Structure

```
pizza-menu-demo/
├── public/
│   ├── favicon.ico
│   ├── index.html
│   ├── logo192.png
│   ├── logo512.png
│   ├── manifest.json
│   ├── robots.txt
│   └── pizzas/
│       ├── focaccia.jpg
│       ├── funghi.jpg
│       ├── margherita.jpg
│       ├── prosciutto.jpg
│       ├── salamino.jpg
│       └── spinaci.jpg
├── src/
│   ├── index.css
│   └── index.js
├── package.json
└── README.md
```

## Getting Started

### Prerequisites

- Node.js (v18 or newer recommended)
- npm (comes with Node.js)

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/pizza-menu-demo.git
   cd pizza-menu-demo
   ```
2. Install dependencies:
   ```sh
   npm install
   ```

### Running the App

Start the development server:

```sh
npm start
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the app.

### Building for Production

To create an optimized production build:

```sh
npm run build
```

## Customization

- To change the menu, edit the `pizzaData` array in [`src/index.js`](src/index.js).
- To update styles, modify [`src/index.css`](src/index.css).
- Pizza images are stored in [`public/pizzas/`](public/pizzas/).

## License

This project is for demo purposes and does not include a license.
