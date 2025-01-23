# Emoji World ❤️

**Emoji World** is a fun and user-friendly platform that allows you to search, browse, and effortlessly copy your favorite emojis. Whether you're looking to express emotions, represent objects, or showcase symbols, Emoji World has got you covered with an extensive collection organized into intuitive categories. Enhance your messaging, social media posts, and documents with ease!

## 💪 Follow me
- **👉 Checkout some more awesome tools at [GetCyber](https://getcyber.me/tools)**
- **👉 Subscribe to my YouTube Channel [GetCyber - YouTube](https://youtube.com/getCyber)**
- **👉 Discord Server [GetCyber - Discord](https://discord.gg/YUf3VpDeNH)**

## 📖 Table of Contents

- [Emoji World ❤️](#emoji-world-️)
  - [💪 Follow me](#-follow-me)
  - [📖 Table of Contents](#-table-of-contents)
  - [🌟 Features](#-features)
  - [📺 Video Demo](#-video-demo)
  - [🚀 Live Demo](#-live-demo)
  - [📁 Repository Structure](#-repository-structure)
    - [🗂️ Directory and File Breakdown](#️-directory-and-file-breakdown)
  - [🛠️ Technologies Used](#️-technologies-used)
  - [📥 Installation](#-installation)
  - [🔧 Development](#-development)
  - [🎨 Customization](#-customization)
  - [📄 License](#-license)
  - [🤝 Contributing](#-contributing)
    - [📝 Guidelines](#-guidelines)
  - [📞 Contact](#-contact)

## 🌟 Features

- **Comprehensive Emoji Library:** Access a vast array of emojis categorized for easy navigation, including Smileys, People, Animals, Food, Travel, Activities, Objects, Symbols, and Flags.
- **Intuitive Search:** Quickly find emojis by typing keywords or their characters.
- **Easy Copy Functionality:** Click on any emoji to copy it directly to your clipboard for seamless use in your messages, posts, or documents.
- **Responsive Design:** Enjoy a consistent and optimized experience across all devices, from desktops to mobile phones.
- **Dark and Light Themes:** Toggle between dark and light modes to suit your preference or system settings.
- **Optimized Performance:** Fast loading times with minified CSS and JavaScript files.
- **Social Integration:** Easily connect with our community through GitHub, YouTube, and Discord.
- **Accessible Interface:** Designed with accessibility in mind, ensuring usability for all users, including those relying on assistive technologies.

## 📺 Video Demo

Check out the demo of our project in action:

[![Video Demo](https://img.youtube.com/vi/q8wK-9QKYpI/0.jpg)](https://youtu.be/q8wK-9QKYpI)

## 🚀 Live Demo

Experience **Emoji World** in action! [Visit Emoji World](https://emoji-world.getcyber.me)

## 📁 Repository Structure

Understanding the repository structure is key to navigating and contributing to the project effectively. Here's an overview of the current setup:

```
emoji-world/
├── apple-touch-icon.png
├── assets/
│   ├── css.min.css
│   ├── js.min.js
│   ├── lodash.min.js
│   ├── og-image.png
│   └── twitter-image.png
├── favicon-96x96.png
├── favicon.ico
├── favicon.svg
├── index.html
├── site.webmanifest
├── src/
│   ├── css.css
│   ├── index-original.html
│   └── js.js
├── web-app-manifest-192x192.png
└── web-app-manifest-512x512.png
```

### 🗂️ Directory and File Breakdown

- **`apple-touch-icon.png`**
  - The icon displayed when users add the web app to their iOS home screen.

- **`assets/`**
  - **Purpose:** Contains all optimized (minified) assets ready for production.
  - **Files:**
    - **`css.min.css`**: Minified CSS stylesheet for styling the application.
    - **`js.min.js`**: Minified JavaScript file handling interactivity and functionalities.
    - **`lodash.min.js`**: Minified version of the Lodash library for utility functions.
    - **`og-image.png`**: Open Graph image used for social media sharing previews.
    - **`twitter-image.png`**: Image optimized for Twitter card previews.

- **Favicon Files:**
  - **`favicon-96x96.png`**, **`favicon.ico`**, **`favicon.svg`**: Various favicon formats for different browsers and devices.

- **`index.html`**
  - The main entry point of the application. It references the minified CSS and JS files from the `assets/` directory.

- **`site.webmanifest`**
  - Configuration file for Progressive Web App (PWA) capabilities, defining how the app appears to the user.

- **`src/`**
  - **Purpose:** Contains all source (non-minified) files for development.
  - **Files:**
    - **`css.css`**: Original CSS stylesheet before minification.
    - **`js.js`**: Original JavaScript file before minification.
    - **`index-original.html`**: Original HTML file used as a template or for development purposes.

- **Web App Manifest Files:**
  - **`web-app-manifest-192x192.png`**, **`web-app-manifest-512x512.png`**: Icons used by the web app manifest for various device resolutions.

## 🛠️ Technologies Used

- **HTML5:** Structuring the web content.
- **CSS3:** Styling and responsive design.
- **JavaScript (ES6):** Interactive functionalities and theme toggling.
- **Lodash:** Utility library for efficient JavaScript operations.
- **Responsive Web Design:** Ensuring the app looks great on all devices.
- **Progressive Web App (PWA) Standards:** Making the app installable and enhancing performance.

## 📥 Installation

To set up **Emoji World** locally, follow these simple steps:

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/Dan-Duran/emoji-world.git
   ```

2. **Navigate to the Project Directory:**

   ```bash
   cd emoji-world
   ```

3. **Open `index.html` in Your Browser:**

   You can open the `index.html` file directly in your preferred web browser or serve it using a local development server for a better experience.

   - **Using Live Server (VS Code Extension):**
     - Install the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension in VS Code.
     - Right-click on `index.html` and select "Open with Live Server".

   - **Using Python's SimpleHTTPServer:**

     ```bash
     # For Python 3.x
     python -m http.server 8000
     ```

     Then, navigate to `http://localhost:8000` in your browser.

## 🔧 Development

If you plan to contribute to the project or customize it further, here's how you can work with the source files:

1. **Source Files Location:**

   All non-minified source files are located in the `src/` directory.

   - **CSS:** `src/css.css`
   - **JavaScript:** `src/js.js`
   - **HTML Template:** `src/index-original.html`

2. **Making Changes:**

   - **Styling:**
     - Edit `src/css.css` to update styles.
     - After making changes, minify the CSS and place the output in `assets/css.min.css`.

   - **JavaScript:**
     - Edit `src/js.js` to update functionalities.
     - After making changes, minify the JS and place the output in `assets/js.min.js`.

3. **Minification:**

   For minifying CSS and JS files, you can use tools like:

   - **Online Minifiers:** [CSS Minifier](https://cssminifier.com/), [JS Minifier](https://jsminifier.com/)
   - **Build Tools:** Integrate build tools like **Webpack**, **Gulp**, or **Parcel** for automated minification.

4. **Testing:**

   After making changes and minifying, refresh the browser to see the updates. Ensure that all functionalities work as expected and that the design remains responsive.

## 🎨 Customization

Customize **Emoji World** to better fit your branding or personal preferences:

- **Themes:**
  - The application supports both dark and light themes.
  - Toggle between themes using the theme switch button in the header.
  - To modify theme colors, update the CSS variables in `assets/css.min.css` (after minification) or better yet, make changes in `src/css.css` before minification.

- **Emojis:**
  - The emoji data is embedded within the JavaScript file (`src/js.js`).
  - To add or remove emojis, edit the corresponding arrays in the source JS file and re-minify.

- **Icons and Images:**
  - Replace `og-image.png` and `twitter-image.png` in the `assets/` directory with your own images to customize social media previews.

- **Favicon:**
  - Update favicon files (`favicon-96x96.png`, `favicon.ico`, `favicon.svg`) with your own branding to personalize the browser tab icon.

## 📄 License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute it as per the license terms.

## 🤝 Contributing

Contributions are welcome! Whether it's reporting bugs, suggesting features, or submitting pull requests, your input helps improve **Emoji World**. Follow these steps to contribute:

1. **Fork the Repository:**

   Click the "Fork" button at the top right of the repository page to create your own copy.

2. **Clone Your Fork:**

   ```bash
   git clone https://github.com/your-username/emoji-world.git
   ```

3. **Create a Branch:**

   ```bash
   git checkout -b feature/YourFeatureName
   ```

4. **Make Your Changes:**

   - Edit source files in the `src/` directory.
   - Ensure you maintain the repository structure.

5. **Commit Your Changes:**

   ```bash
   git commit -m "Add feature: Your Feature Description"
   ```

6. **Push to Your Fork:**

   ```bash
   git push origin feature/YourFeatureName
   ```

7. **Create a Pull Request:**

   Go to your forked repository on GitHub and click "Compare & pull request". Provide a clear description of your changes and submit.

### 📝 Guidelines

- **Code Quality:** Ensure your code is clean, well-documented, and follows best practices.
- **Testing:** Test your changes thoroughly before submitting a pull request.
- **Respect Licensing:** Make sure your contributions comply with the project's MIT License.

## 📞 Contact

Have questions or need support? Reach out through the following channels:

- **GitHub Issues:** Open an issue in the repository for bug reports or feature requests.
- **Discord:** Join our community [here](https://discord.gg/YUf3VpDeNH) to chat with other users and the developer.
- **YouTube:** Subscribe and comment on our [YouTube channel](https://youtube.com/@GetCyber).

---

Thank you for checking out **Emoji World**! We hope it enhances your digital conversations and creativity. Feel free to contribute, report issues, or suggest features to help improve the project.

---

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg) ![GitHub issues](https://img.shields.io/github/issues/Dan-Duran/emoji-world.svg) ![GitHub forks](https://img.shields.io/github/forks/Dan-Duran/emoji-world.svg) ![GitHub stars](https://img.shields.io/github/stars/Dan-Duran/emoji-world.svg) ![GitHub license](https://img.shields.io/github/license/Dan-Duran/emoji-world.svg)

---