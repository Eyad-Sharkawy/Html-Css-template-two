# Kasper - Template Two

A modern, responsive HTML template built with Sass (SCSS). This project is currently **work in progress** and showcases a clean, professional design for business websites.

## 🚧 Project Status

**⚠️ WORK IN PROGRESS** - This project is actively being developed and is not yet complete. Features and components are being added incrementally.

## 📋 Project Overview

Kasper is a responsive HTML template featuring:
- Modern, clean design aesthetic
- Mobile-first responsive layout
- Modular Sass architecture
- Interactive components
- Professional business website structure

## 🏗️ Project Structure

```
template-two/
├── css/                 # Compiled CSS files
│   ├── main.css        # Main stylesheet
│   ├── normalize.css   # CSS reset/normalize
│   └── all.min.css    # Font Awesome CSS
├── scss/               # Source Sass files
│   ├── components/     # Component-specific styles
│   │   ├── _header.scss
│   │   ├── _landing-page.scss
│   │   ├── _services.scss
│   │   ├── _design.scss
│   │   ├── _portfolio.scss
│   │   ├── _video.scss
│   │   ├── _about-us.scss
│   │   ├── _stats.scss
│   │   ├── _skills-testimonials.scss
│   │   └── _quote.scss
│   ├── helpers/        # Sass utilities
│   │   ├── _variables.scss
│   │   ├── _mixins.scss
│   │   └── _global.scss
│   └── main.scss       # Main Sass entry point
├── media/              # Media assets
│   ├── images/         # Image files
│   └── videos/         # Video files
├── webfonts/           # Font Awesome webfonts
├── index.html          # Main HTML file
├── index.js            # JavaScript file
└── package.json        # Project configuration
```

## 🎨 Features

### Completed Components
- **Header**: Navigation with logo and menu
- **Landing Page**: Hero section with overlay and navigation arrows
- **Services**: Service showcase with icons and descriptions
- **Design**: Design features section
- **Portfolio**: Portfolio grid layout
- **Video**: Video section with overlay
- **About Us**: Company information section
- **Stats**: Statistics/numbers section
- **skills/testimonials**: Testimonial/Skills

### Design Features
- Responsive grid system
- Modern typography using Google Fonts (Open Sans)
- Font Awesome icon integration
- CSS animations and transitions
- Mobile-first approach
- Clean, professional color scheme

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **Sass/SCSS**: Advanced CSS preprocessing
- **CSS3**: Modern styling features
- **JavaScript**: Interactive functionality
- **Font Awesome**: Icon library
- **Google Fonts**: Typography

## 🚀 Getting Started

### Prerequisites
- Modern web browser
- Sass compiler (if working with source files)

### Installation
1. Clone or download this repository
2. Open `index.html` in your web browser
3. For development, ensure you have Sass installed to compile SCSS files

### Development Setup
```bash
# Install Sass globally (if not already installed)
npm install -g sass

# Watch and compile Sass files
sass --watch scss:css

# Or compile once
sass scss/main.scss css/main.css
```

## 📱 Responsive Design

The template is built with a mobile-first approach and includes:
- Responsive navigation
- Flexible grid layouts
- Adaptive typography
- Mobile-optimized components

## 🎯 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 🔧 Customization

### Sass Variables
Edit `scss/helpers/_variables.scss` to customize:
- Color scheme
- Typography
- Spacing
- Breakpoints

### Component Styling
Each component has its own SCSS file in the `scss/components/` directory for easy customization.

## 📝 Development Notes

### Current Status
- Basic structure and layout completed
- Core components implemented
- Responsive design in progress
- JavaScript functionality being developed

### Next Steps
- Complete remaining sections
- Add more interactive features
- Optimize performance
- Add documentation
- Implement form functionality
- Add more animations

## 🤝 Contributing

This is a personal project, but suggestions and feedbacks are welcomed!

## 📄 License

This project is for personal/educational use.

## 📞 Contact

For questions or feedback about this template, please reach out through the project repository.

---

**Note**: This project is actively being developed. Features, structure, and documentation may change as development progresses.
