# OpieWorks LLC - Landing Page

A modern, interactive landing page for OpieWorks LLC, featuring 3D animations and creative development services showcase.

## 🌟 Features

- **Interactive 3D Background**: Choose between a Three.js animated torus knot or Vanta.js globe animation
- **Responsive Design**: Fully responsive layout using Tailwind CSS
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Service Showcase**: Highlights key services including web development, content creation, UX/UI design, videography, and photography
- **Contact Integration**: Direct links to LinkedIn and email contact
- **Performance Optimized**: Lightweight with CDN-delivered assets

## 🛠️ Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Custom styling with Tailwind CSS framework
- **JavaScript**: Interactive functionality and animations
- **Three.js**: 3D graphics and animations
- **Vanta.js**: Animated background effects
- **Feather Icons**: Clean, consistent iconography

## 🚀 Getting Started

### Prerequisites

No build process required! This is a static HTML page that runs directly in the browser.

### Installation

1. Clone the repository:
   ```bash
   git clone [repository-url]
   cd opieworks-landing
   ```

2. Open `index.html` in your web browser or serve it using a local server:
   ```bash
   # Using Python
   python -m http.server 8000

   # Using Node.js (if you have http-server installed)
   npx http-server

   # Using PHP
   php -S localhost:8000
   ```

3. Navigate to `http://localhost:8000` in your browser

## 🎨 Customization

### Background Animation

The page supports two different background animations. You can switch between them by modifying the JavaScript at the bottom of `index.html`:

```javascript
// For Three.js 3D scene (animated torus knot)
init3DScene();
// initVanta();

// For Vanta.js globe animation
// init3DScene();
initVanta();
```

### Colors and Styling

The primary brand color is orange (`#F97316`). You can customize colors by:
- Modifying the CSS custom properties
- Updating Tailwind CSS classes
- Changing the 3D object colors in the JavaScript

### Services

Update the services grid in the HTML to reflect your offerings:
```html
<div class="bg-gray-800 bg-opacity-50 p-3 rounded-lg text-center">Your Service</div>
```

## 📁 Project Structure

```
├── index.html          # Main landing page
├── README.md           # Project documentation
├── package.json        # Project metadata
├── CNAME              # Domain configuration
└── archive/           # Archived assets
    └── original-landing-page/
        ├── *.svg      # Logo files
        ├── *.png      # Social media icons
        └── *.txt      # License files
```

## 🌐 Live Demo

Visit the live site at: [Your domain here]

## 📧 Contact

- **Email**: james@opieworks.com
- **LinkedIn**: [theopie](https://www.linkedin.com/in/theopie)

## 📄 License

This project is licensed under the MIT License - see the archive folder for license details.

## 🤝 Contributing

This is a personal/company landing page, but suggestions and improvements are welcome! Feel free to open an issue or submit a pull request.

---

**OpieWorks LLC** - Creative Development Solutions