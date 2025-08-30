# Template Two - Modern SCSS & HTML Project

A professional, responsive website template built with pure SCSS and HTML, featuring modern CSS architecture and best practices.

## 🚀 Features

- **Pure SCSS & HTML** - No JavaScript dependencies
- **Component-based Architecture** - Modular and maintainable SCSS structure
- **Responsive Design** - Mobile-first approach with CSS Grid and Flexbox
- **Modern CSS Features** - CSS Grid, Flexbox, CSS Variables, and more
- **Performance Optimized** - Minified CSS with source maps
- **Professional Structure** - Industry-standard project organization

## 📁 Project Structure

```
template-two/
├── scss/                          # SCSS source files
│   ├── helpers/                   # Global helpers and utilities
│   │   ├── _variables.scss       # Color, font, and spacing variables
│   │   ├── _mixins.scss          # Reusable SCSS mixins
│   │   └── _global.scss          # Global styles and resets
│   ├── components/                # Component-specific styles
│   │   ├── _header.scss          # Header navigation styles
│   │   ├── _landing-page.scss    # Hero section styles
│   │   ├── _services.scss        # Services section styles
│   │   ├── _portfolio.scss       # Portfolio grid styles
│   │   ├── _about-us.scss        # About section styles
│   │   ├── _stats.scss           # Statistics section styles
│   │   ├── _skills-testimonials.scss # Skills and testimonials
│   │   ├── _pricing.scss         # Pricing plans styles
│   │   ├── _subscribe.scss       # Newsletter subscription
│   │   ├── _contact-us.scss      # Contact form styles
│   │   └── _footer.scss          # Footer styles
│   └── main.scss                 # Main SCSS entry point
├── css/                           # Compiled CSS files
│   ├── main.css                  # Development CSS
│   ├── main.min.css              # Production minified CSS
│   ├── main.css.map              # Source map for debugging
│   ├── normalize.css             # CSS reset/normalize
│   └── normalize.min.css         # Minified normalize
├── media/                         # Media assets
│   ├── images/                   # Image files
│   └── videos/                   # Video files
├── webfonts/                      # Font Awesome icons
├── index.html                     # Main HTML file
├── package.json                   # Project configuration
└── README.md                      # This file
```

## 🛠️ Setup & Installation

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Eyad-Sharkawy/Html-Css-template-two
   cd template-two
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

## 🚀 Development

### Available Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Start development with live SCSS compilation |
| `npm run watch` | Watch SCSS files for changes |
| `npm run build` | Build minified CSS for production |
| `npm run build:dev` | Build unminified CSS for development |
| `npm run build:prod` | Build minified CSS for production |
| `npm run clean` | Remove all generated CSS files |
| `npm run serve` | Start local development server |

### Development Workflow

1. **Start Development:**
   ```bash
   npm run dev
   ```
   This will watch your SCSS files and automatically compile them to CSS.

2. **Build for Production:**
   ```bash
   npm run build
   ```
   This creates minified CSS with source maps.

3. **Preview Your Site:**
   ```bash
   npm run serve
   ```
   Opens your site in a local development server.

## 🎨 SCSS Architecture

### Variables (`_variables.scss`)
- **Colors**: Primary colors, text colors, backgrounds
- **Typography**: Font families and sizes
- **Spacing**: Consistent spacing units using rem

### Mixins (`_mixins.scss`)
- **`prefixer`**: Vendor prefix automation
- **`overlay`**: Common overlay pattern
- **`under-line`**: Decorative underline styling
- **`title`**: Section title styling with decorative elements

### Component Structure
Each component follows a consistent pattern:
- BEM-like naming convention
- Responsive design with mobile-first approach
- Modular and reusable styles

## 📱 Responsive Design

The project uses a mobile-first approach with these breakpoints:
- **Mobile**: 0px - 575px
- **Small**: 576px - 767px
- **Medium**: 768px - 991px
- **Large**: 992px - 1199px
- **Extra Large**: 1200px+

## 🎯 Key Components

### Header
- Fixed navigation with logo
- Responsive mobile menu
- Search functionality

### Landing Page
- Full-screen hero section
- Background image with overlay
- Call-to-action content

### Services
- Grid layout for service items
- Icon integration with Font Awesome
- Responsive card design

### Portfolio
- Filterable image grid
- Hover effects and overlays
- Responsive grid system

### Contact Form
- Structured contact information
- Form validation ready
- Responsive layout

## 🔧 Customization

### Colors
Modify colors in `scss/helpers/_variables.scss`:
```scss
$main-color: #19c8fa;           // Primary brand color
$text-color: #777;              // Main text color
$dark-background: #1f2021;      // Dark section backgrounds
```

### Typography
Update fonts in `scss/helpers/_variables.scss`:
```scss
$main-font: "Open Sans", sans-serif;
```

### Spacing
Adjust spacing units in `scss/helpers/_variables.scss`:
```scss
$section-padding: 6.25rem;      // Section padding
```

## 📊 Performance Features

- **CSS Minification**: Reduces file size by ~30%
- **Source Maps**: Enables debugging of minified CSS
- **Optimized Images**: Web-optimized media files
- **Efficient CSS**: Minimal redundancy and optimized selectors

## 🌐 Browser Support

- **Modern Browsers**: Chrome 90+, Firefox 88+, Safari 14+, Edge 90+
- **CSS Features**: CSS Grid, Flexbox, CSS Variables, CSS Transitions
- **Fallbacks**: Graceful degradation for older browsers

## 📝 Best Practices Used

- **Semantic HTML**: Proper use of HTML5 elements
- **CSS Architecture**: Component-based SCSS structure
- **Responsive Design**: Mobile-first approach
- **Performance**: Minified CSS and optimized assets
- **Accessibility**: Semantic markup and proper contrast
- **Maintainability**: Modular SCSS with clear naming conventions

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- Font Awesome for icons
- Google Fonts for typography
- Normalize.css for CSS reset

## 📞 Support

For questions or support, please open an issue in the repository.

---

**Built with ❤️ using modern web technologies** 
