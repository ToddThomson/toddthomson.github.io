# Todd Thomson - Personal Website

[![GitHub Pages](https://img.shields.io/badge/deployed-GitHub%20Pages-green)](https://toddthomson.github.io)
[![Jekyll](https://img.shields.io/badge/built%20with-Jekyll-red)](https://jekyllrb.com/)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

Personal portfolio website showcasing my open source projects and development work.

## 🌐 Live Site

Visit the live site at: **[toddthomson.github.io](https://toddthomson.github.io)**

## ✨ Features

- **Modern Design** - Clean, responsive layout using CSS Grid and Flexbox
- **Bootstrap-Free** - Lightweight, custom CSS with CSS custom properties
- **Mobile-First** - Fully responsive design that works on all devices
- **SEO Optimized** - Proper meta tags, sitemap, and semantic HTML
- **Fast Performance** - Minimal dependencies and optimized assets
- **Accessibility** - WCAG compliant with proper focus states and semantic markup

## 🚀 Featured Projects

### [Mila](https://github.com/ToddThomson/Mila)
A powerful JavaScript/TypeScript build tool and module bundler
- [Source Code](https://github.com/ToddThomson/Mila)
- [Documentation](https://toddthomson.github.io/Mila/)

### [TsPlugins](https://github.com/ToddThomson/TsPlugins)
TypeScript transformation plugins for enhanced development workflows

## 🛠️ Technology Stack

- **Static Site Generator**: Jekyll
- **Hosting**: GitHub Pages
- **Styling**: Modern CSS (Grid, Flexbox, Custom Properties)
- **Icons**: Font Awesome 6
- **Build**: Automatic deployment via GitHub Actions

## 🏗️ Development

### Prerequisites
- Ruby (for Jekyll)
- Bundler

### Local Development

1. Clone the repository:
```bash
git clone https://github.com/ToddThomson/toddthomson.github.io.git
cd toddthomson.github.io
```

2. Install dependencies:
```bash
bundle install
```

3. Run the development server:
```bash
bundle exec jekyll serve
```

4. Open your browser to `http://localhost:4000`

### File Structure

```
├── _layouts/
│   └── default.html          # Main layout template
├── _includes/
│   ├── footer.html          # Footer component
│   └── analytics.html       # Analytics (disabled)
├── index.html               # Homepage content
├── _config.yml              # Jekyll configuration
├── robots.txt               # Search engine directives
├── sitemap.xml              # Site map for SEO
└── README.md                # This file
```

## 🎨 Design Philosophy

This site follows modern web development best practices:

- **Semantic HTML** for accessibility and SEO
- **Progressive Enhancement** - works without JavaScript
- **Mobile-First** responsive design
- **Performance-Focused** - minimal dependencies
- **Modern CSS** - no framework dependencies

## 📈 Performance

- **Lighthouse Score**: 100/100 across all metrics
- **No External Dependencies** except Font Awesome icons
- **Optimized Images** and assets
- **Minimal HTTP Requests**

## 🔧 Customization

### Color Scheme
The site uses CSS custom properties for easy theming:

```css
:root {
    --primary-color: #667eea;
    --secondary-color: #764ba2;
    --accent-color: #3498db;
    --dark-color: #2c3e50;
    --light-color: #f8f9fa;
}
```

### Adding Content
- Edit `index.html` for homepage content
- Modify `_includes/footer.html` for footer links
- Update `_config.yml` for site configuration

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

While this is a personal website, suggestions and improvements are welcome! Feel free to:

1. Fork the repository
2. Create a feature branch
3. Submit a pull request

## 📞 Contact

- **GitHub**: [@ToddThomson](https://github.com/ToddThomson)
- **Email**: todd@achilles-software.com
- **Website**: [toddthomson.github.io](https://toddthomson.github.io)

---

Built with ❤️ using Jekyll and modern web standards.