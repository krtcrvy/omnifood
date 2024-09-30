# Omnifood Project Documentation

## Table of Contents

1. Introduction
2. [Project Structure](#project-structure)
3. [Technologies Used](#technologies-used)
4. [Setup and Installation](#setup-and-installation)
5. Features
6. [Responsive Design](#responsive-design)
7. [Progressive Web App](#progressive-web-app)
8. [CSS Styling](#css-styling)
9. [JavaScript Functionality](#javascript-functionality)
10. Manifest
11. [Contact Information](#contact-information)

## Introduction

Omnifood is a landing page for a modern web application designed to provide users with a seamless experience in exploring and ordering meals. This project includes a responsive design, various interactive elements, and a manifest for progressive web app capabilities.

## Project Structure

```
content.md
css/
	general.css
	queries.css
	style.css
img/
	app/
	customers/
	gallery/
	logos/
	meals/
index.html
js/
	script.js
manifest.webmanifest
public/
README.md
```

## Technologies Used

- HTML
- CSS
- JavaScript
- Progressive Web App (PWA) Manifest

## Setup and Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/omnifood.git
   ```
2. Navigate to the project directory:
   ```sh
   cd omnifood
   ```
3. Open [`index.html`](command:_github.copilot.openRelativePath?%5B%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2FC%3A%2FUsers%2Fkarbi%2FDocuments%2FGitHub%2Fomnifood%2Findex.html%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%2C%2244281ad9-3fe6-44cc-a043-eacdf5472384%22%5D "c:\\Users\karbi\Documents\GitHub\omnifood\index.html") in your browser to view the landing page.

## Features

- **Responsive Design**: The layout adjusts to different screen sizes.
- **Interactive Elements**: Includes various interactive elements for a better user experience.
- **Progressive Web App**: Includes a manifest for PWA capabilities.

## Responsive Design

The project uses media queries to ensure the design is responsive. Key CSS files:

- [`css/queries.css`](command:_github.copilot.openRelativePath?%5B%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2FC%3A%2FUsers%2Fkarbi%2FDocuments%2FGitHub%2Fomnifood%2Fcss%2Fqueries.css%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%2C%2244281ad9-3fe6-44cc-a043-eacdf5472384%22%5D "c:\\Users\karbi\Documents\GitHub\omnifood\css\queries.css")
- [`css/style.css`](command:_github.copilot.openRelativePath?%5B%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2FC%3A%2FUsers%2Fkarbi%2FDocuments%2FGitHub%2Fomnifood%2Fcss%2Fstyle.css%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%2C%2244281ad9-3fe6-44cc-a043-eacdf5472384%22%5D "c:\\Users\karbi\Documents\GitHub\omnifood\css\style.css")

Example from [`queries.css`](command:_github.copilot.openRelativePath?%5B%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2Fc%3A%2FUsers%2Fkarbi%2FDocuments%2FGitHub%2Fomnifood%2Fcss%2Fqueries.css%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%2C%2244281ad9-3fe6-44cc-a043-eacdf5472384%22%5D "c:\\Users\karbi\Documents\GitHub\omnifood\css\queries.css"):

```css
@media (max-width: 75em) {
  .no-flexbox-gap .main-nav-list li:not(:last-child) {
    margin-right: 3.2rem;
  }
}
@media (max-width: 59em) {
  .no-flexbox-gap .main-nav-list li:not(:last-child) {
    margin-right: 0;
    margin-bottom: 4.8rem;
  }
}
```

## Progressive Web App

The project includes a manifest file to enable PWA capabilities:

- [`manifest.webmanifest`](command:_github.copilot.openRelativePath?%5B%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2FC%3A%2FUsers%2Fkarbi%2FDocuments%2FGitHub%2Fomnifood%2Fmanifest.webmanifest%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%2C%2244281ad9-3fe6-44cc-a043-eacdf5472384%22%5D "c:\\Users\karbi\Documents\GitHub\omnifood\manifest.webmanifest")

Example from [`manifest.webmanifest`](command:_github.copilot.openRelativePath?%5B%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2FC%3A%2FUsers%2Fkarbi%2FDocuments%2FGitHub%2Fomnifood%2Fmanifest.webmanifest%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%2C%2244281ad9-3fe6-44cc-a043-eacdf5472384%22%5D "c:\\Users\karbi\Documents\GitHub\omnifood\manifest.webmanifest"):

```json
{
  "icons": [
    { "src": "img/favicon-192.png", "type": "image/png", "sizes": "192x192" },
    { "src": "img/favicon-512.png", "type": "image/png", "sizes": "512x512" }
  ]
}
```

## CSS Styling

The project uses multiple CSS files for styling:

- [`css/general.css`](command:_github.copilot.openRelativePath?%5B%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2FC%3A%2FUsers%2Fkarbi%2FDocuments%2FGitHub%2Fomnifood%2Fcss%2Fgeneral.css%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%2C%2244281ad9-3fe6-44cc-a043-eacdf5472384%22%5D "c:\\Users\karbi\Documents\GitHub\omnifood\css\general.css")
- [`css/queries.css`](command:_github.copilot.openRelativePath?%5B%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2FC%3A%2FUsers%2Fkarbi%2FDocuments%2FGitHub%2Fomnifood%2Fcss%2Fqueries.css%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%2C%2244281ad9-3fe6-44cc-a043-eacdf5472384%22%5D "c:\\Users\karbi\Documents\GitHub\omnifood\css\queries.css")
- [`css/style.css`](command:_github.copilot.openRelativePath?%5B%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2FC%3A%2FUsers%2Fkarbi%2FDocuments%2FGitHub%2Fomnifood%2Fcss%2Fstyle.css%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%2C%2244281ad9-3fe6-44cc-a043-eacdf5472384%22%5D "c:\\Users\karbi\Documents\GitHub\omnifood\css\style.css")

Example from [`style.css`](command:_github.copilot.openRelativePath?%5B%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2Fc%3A%2FUsers%2Fkarbi%2FDocuments%2FGitHub%2Fomnifood%2Fcss%2Fstyle.css%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%2C%2244281ad9-3fe6-44cc-a043-eacdf5472384%22%5D "c:\\Users\karbi\Documents\GitHub\omnifood\css\style.css"):

```css
.footer {
  padding: 12.8rem 0;
  border-top: 1px solid #eee;
}
```

## JavaScript Functionality

JavaScript is used to enhance the functionality of the page:

- [`js/script.js`](command:_github.copilot.openRelativePath?%5B%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2FC%3A%2FUsers%2Fkarbi%2FDocuments%2FGitHub%2Fomnifood%2Fjs%2Fscript.js%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%2C%2244281ad9-3fe6-44cc-a043-eacdf5472384%22%5D "c:\\Users\karbi\Documents\GitHub\omnifood\js\script.js")

Example from [`script.js`](command:_github.copilot.openRelativePath?%5B%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2Fc%3A%2FUsers%2Fkarbi%2FDocuments%2FGitHub%2Fomnifood%2Fjs%2Fscript.js%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%2C%2244281ad9-3fe6-44cc-a043-eacdf5472384%22%5D "c:\\Users\karbi\Documents\GitHub\omnifood\js\script.js"):

```js
function checkFlexGap() {
  var flex = document.createElement("div");
  flex.style.display = "flex";
  flex.style.flexDirection = "column";
  flex.style.rowGap = "1px";

  flex.appendChild(document.createElement("div"));
  flex.appendChild(document.createElement("div"));

  document.body.appendChild(flex);
  var isSupported = flex.scrollHeight === 1;
  flex.parentNode.removeChild(flex);
  console.log(isSupported);

  if (!isSupported) document.body.classList.add("no-flexbox-gap");
}
checkFlexGap();
```

## Manifest

The manifest file for PWA capabilities:

- [`manifest.webmanifest`](command:_github.copilot.openRelativePath?%5B%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2FC%3A%2FUsers%2Fkarbi%2FDocuments%2FGitHub%2Fomnifood%2Fmanifest.webmanifest%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%2C%2244281ad9-3fe6-44cc-a043-eacdf5472384%22%5D "c:\\Users\karbi\Documents\GitHub\omnifood\manifest.webmanifest")

## Contact Information

For any inquiries, please contact:

- **Address**: 623 Harrison St., 2nd Floor, San Francisco, CA 94107
- **Phone**: 415-201-6370
- **Email**: hello@omnifood.com
