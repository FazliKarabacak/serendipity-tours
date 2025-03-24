# Serendipity Tours

A professional travel and tours marketing website built with Hugo and Tailwind CSS.

## 🌟 Overview

Serendipity Tours is a travel company specializing in unique, unforgettable travel experiences. This website showcases our tour offerings, travel guides, and company information.

## 🛠️ Technology Stack

- **[Hugo](https://gohugo.io/)** - Fast and flexible static site generator
- **[Tailwind CSS](https://tailwindcss.com/)** - Utility-first CSS framework
- **JavaScript** - For interactive elements and animations
- **Responsive Design** - Optimized for all devices

## 🚀 Features

- Responsive tour listings and details
- SEO-optimized content structure
- Fast-loading pages with optimized assets
- Contact forms for inquiries and bookings
- Blog section for travel guides and tips

## 📂 Project Structure

```
serendipity-tours/
├── archetypes/          # Content templates
├── assets/              # CSS, JS, and other assets
│   └── css/             # Tailwind CSS source
├── content/             # Markdown content
│   ├── tours/           # Tour listings
│   ├── blog/            # Blog posts
│   └── pages/           # Static pages
├── layouts/             # Hugo templates
│   ├── _default/        # Default templates
│   ├── partials/        # Reusable components
│   └── shortcodes/      # Content shortcodes
├── static/              # Static assets
│   ├── images/          # Images
│   └── fonts/           # Custom fonts
├── hugo.toml            # Hugo configuration
├── netlify.toml         # Netlify configuration
├── package.json         # Node.js dependencies
└── tailwind.config.js   # Tailwind configuration
```

## 🔧 Development

### Prerequisites

- [Hugo](https://gohugo.io/getting-started/installing/) (Extended version)
- [Node.js](https://nodejs.org/) and npm

### Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/FazliKarabacak/serendipity-tours.git
   cd serendipity-tours
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   hugo server -D
   ```

4. View the site at http://localhost:1313/

5. hugo --gc --minify 

6. netlify deploy --prod

### Building for Production

```bash
hugo --minify
```

Output will be in the `public/` directory.

## 📊 Analytics

The site uses Google Analytics for visitor tracking and performance monitoring.

## 🚢 Deployment

This site is deployed via Netlify with continuous integration from the GitHub repository.

## 📝 License

© 2025 Serendipity Tours. All rights reserved.

## 📞 Contact

For questions about this project, please reach out to:
[Your Contact Information]