# QR Code Generator

A lightweight, responsive QR code generator web application built with HTML, CSS, and JavaScript.

![QR Code Generator Screenshot](https://i.imgur.com/JQZ1l4D.png)

## Features

- Generate QR codes from text or URLs
- Adjustable QR code size (Small, Medium, Large)
- Instant preview of generated QR code
- Download functionality (PNG format)
- Clean, modern UI with responsive design
- Toast notifications for user feedback
- Loading spinner during generation
- Helpful tooltips for guidance
- Keyboard support (Enter key to generate)

## Technologies Used

- HTML5
- CSS3 (with CSS Variables)
- JavaScript (Vanilla JS)
- [QRCode.js](https://github.com/davidshimjs/qrcodejs) library
- [Font Awesome](https://fontawesome.com/) for icons
- Google Fonts (Inter)

## Live Demo

[View Live Demo](https://your-username.github.io/qr-code-generator/)

## Installation

No installation required - this is a client-side only application. Simply open `index.html` in any modern browser.

For local development:

1. Clone the repository:
```bash
git clone https://github.com/your-username/qr-code-generator.git
Open index.html in your browser.

Deployment
GitHub Pages
Ensure your project is pushed to GitHub

Go to your repository Settings

Navigate to Pages in the left sidebar

Select "Deploy from a branch" and choose your main branch

Click Save

Your app will be available at: https://your-username.github.io/qr-code-generator/

Netlify
Drag and drop the project folder to Netlify's drop zone

Or connect your GitHub repository to Netlify

Usage
Enter text or URL in the input field

Select desired QR code size

Click "Generate" button

Once generated, click "Save" to download the QR code

Customization
You can easily customize the appearance by modifying the CSS variables in the :root selector:

css
:root {
  --primary-color: #4361ee;       /* Main brand color */
  --primary-hover: #3a56d4;      /* Hover state for primary color */
  --secondary-color: #f8f9fa;    /* Background color for inputs */
  --text-color: #2b2d42;         /* Main text color */
  --light-gray: #e9ecef;         /* Border and subtle UI elements */
  --medium-gray: #adb5bd;        /* Placeholder and secondary text */
  --white: #ffffff;              /* Background color */
}
Browser Support
The application works on all modern browsers including:

Chrome

Firefox

Safari

Edge

Opera

Contributing
Contributions are welcome! Please follow these steps:

Fork the project

Create your feature branch (git checkout -b feature/AmazingFeature)

Commit your changes (git commit -m 'Add some AmazingFeature')

Push to the branch (git push origin feature/AmazingFeature)

Open a Pull Request

License
Distributed under the MIT License. See LICENSE for more information.

Acknowledgements
QRCode.js - QR code generation library

Font Awesome - Beautiful icons

Google Fonts - Inter font family
