# Vera Website

Bootstrap Business website for software solutions, but could easily be changed to fit any business. Dark-themed design with modals and other features.

<img src="./images/screen.png" />

## Features

- Dark design with bright buttons & text for contrast
- Responsive design
- Replaceme script for rolling words
- Navbar scroll effect
- Video modal
- Animated play button
- Pricing grid
- Styled modals for projects
- Font awesome icons

## Usage

This website is built with [Bootstrap](https://getbootstrap.com/) and [Sass](https://sass-lang.com/). It uses [Font Awesome](https://fontawesome.com/) for icons.

In order to customize this website, you need to install [Node.js](https://nodejs.org/en/). Then, clone this repository and run:

```bash
npm install
```

This will install Bootstrap, Sass and Font Awesome. To build your CSS files from Sass, run:

```bash
npm run sass:build
```

To watch your Sass files for changes, run:

```bash
npm run sass:watch
```

You can add Bootstrap variables to the `bootstrap.scss` file. You can look at the file `node_modules/bootstrap/dist/scss/_variables.scss` for a list of all the variables. Do NOT edit the `variables.scss` file directly, as it will be overwritten when you update Bootstrap.

To add your own custom styles, use the `styles.scss` file.
