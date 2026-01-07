# 🛍️ Myntra Clone

A  e-commerce website clone of Myntra, India's leading online fashion and lifestyle platform. Built with HTML5 and CSS3 to replicate the core UI/UX of the original platform.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [Contact](#contact)

## 🔍 Overview

This project is a front-end clone of the Myntra website, designed to practice and demonstrate web development skills. It replicates the home page interface with a focus on responsive design, clean code, and modern CSS practices.

**Live Demo**: [View Demo](https://mohangc07.github.io/myntraclone/)

## ✨ Features

- **Responsive Navigation Bar**: Header with logo, menu items, and user actions
- **Search Functionality**: Search bar with icon integration
- **Category Menu**: Quick access to MEN, WOMEN, KIDS, HOME & LIVING, BEAUTY, and STUDIO sections
- **User Profile Section**: Profile, Wishlist, and Bag icons for user interaction
- **Hero Banner**: Full-width promotional banner
- **Brand Showcase**: Product grid displaying Nike brand items
- **Clean UI**: Shadow effects and modern design aesthetics
- **Font Awesome Icons**: Professional icons for enhanced UX


## 🚀 Installation

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- A code editor (VS Code, Sublime Text, Atom) - optional

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/MohanGC07/myntraclone.git
   ```

2. **Navigate to the project directory**
   ```bash
   cd myntraclone
   ```

3. **Navigate to the Myntra folder**
   ```bash
   cd Myntra
   ```

4. **Open in browser**
   - Double-click on `home.html`, or
   - Right-click `home.html` → Open with → Your Browser
   - Or use Live Server extension in VS Code

## 📁 Project Structure

```
MYNTRACLONE/
│
└── Myntra/
    ├── images/
    │   ├── myntralogo.png
    │   ├── banner.avif
    │   └── nike1.jpg
    │
    ├── home.html
    └── style.css
    |--- readme.md
```

### File Descriptions

- **`home.html`**: Main landing page with navigation, banner, and product sections
- **`style.css`**: Stylesheet containing all design and layout rules
- **`images/`**: Directory containing all image assets (logo, banner, products)

## 🛠️ Technologies Used

### Core Technologies
- **HTML5**: Semantic markup and structure
- **CSS3**: Styling, flexbox layout, and responsive design
- **Font Awesome 6.7.2**: Icon library for UI elements

### CSS Features Used
- Flexbox for responsive layouts
- Box shadows for depth and elevation
- CSS Reset for cross-browser consistency
- Custom styling for forms and inputs

## 🎨 Design Features

### Header Component
- Fixed navigation with logo and menu
- Integrated search bar with icon
- User action icons (Profile, Wishlist, Bag)
- Box shadow for visual separation

### Layout
- Full-width responsive banner
- Grid-based product display
- Consistent spacing and margins
- Shadow effects for card elements

### Typography
- Sans-serif font family
- Bold text for emphasis
- Varied font sizes for hierarchy

## 🔧 Customization

### Changing Colors
Edit the CSS variables in `style.css`:
```css
/* Example: Change header shadow */
.header {
    box-shadow: 0px 2px 10px 0px rgba(0,0,0,0.5);
}
```

### Adding More Products
1. Add product images to the `images/` folder
2. Update the HTML in `home.html`:
```html
<div class="brandColumn">
    <img src="images/your-product.jpg" alt="product" height="300px" width="300px">
</div>
```

### Modifying Layout
Adjust the grid spacing in `style.css`:
```css
.brandRow {
    gap: 1%; /* Adjust spacing between products */
}
```

## 🗺️ Roadmap

- [ ] Add responsive design for mobile devices
- [ ] Implement JavaScript for interactive features
- [ ] Create additional pages (Product, Cart, Checkout)
- [ ] Add hover effects on product cards
- [ ] Implement filter and sort functionality
- [ ] Add footer section
- [ ] Create product detail modal
- [ ] Implement shopping cart functionality
- [ ] Add user authentication pages

## 🤝 Contributing

Contributions are welcome! Follow these steps to contribute:

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. **Commit your changes**
   ```bash
   git commit -m 'Add some AmazingFeature'
   ```
4. **Push to the branch**
   ```bash
   git push origin feature/AmazingFeature
   ```
5. **Open a Pull Request**




## ⚠️ Disclaimer

This is a clone project created for educational purposes only. All Myntra branding, logos, and trademarks belong to their respective owners. This project is not affiliated with, endorsed by, or connected to Myntra or any of its subsidiaries.

## 👤 Author

**Mohan GC**
- GitHub: [@MohanGC07](https://github.com/MohanGC07)
- Repository: [myntraclone](https://github.com/MohanGC07/myntraclone)

## 🙏 Acknowledgments

- Design inspiration from [Myntra](https://www.myntra.com)
- Icons provided by [Font Awesome](https://fontawesome.com)
- Community support from Stack Overflow and GitHub

## 📞 Support

If you have any questions or run into issues:
- **Open an issue**: [Create Issue](https://github.com/MohanGC07/myntraclone/issues)
- **Discussion**: [Start a Discussion](https://github.com/MohanGC07/myntraclone/discussions)

## 🌟 Show Your Support

Give a ⭐️ if you like this project!

---

**Made with ❤️ by Mohan GC**

Last Updated: January 2026