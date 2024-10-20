# Science News Magazine

A modern, professional website for a science news magazine that focuses on making complex scientific research accessible to an educated general audience.

## 🚀 Features

- Clean, minimalist design prioritizing readability
- Responsive layout for various screen sizes
- Featured article section for highlighting important research
- Latest research grid for showcasing multiple articles
- Sticky header with navigation and search functionality
- Footer with about information, quick links, social media, and newsletter subscription

## 🛠️ Technologies Used

- [Astro](https://astro.build/) - Static Site Generator
- [TypeScript](https://www.typescriptlang.org/) - For type-safe JavaScript
- Custom CSS for styling

## 📦 Getting Started

### Prerequisites

- Node.js (v14.15.0 or later)
- npm (v6.14.8 or later)

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/science-news-magazine.git
   ```

2. Navigate to the project directory:
   ```
   cd science-news-magazine
   ```

3. Install dependencies:
   ```
   npm install
   ```

4. Start the development server:
   ```
   npm run dev
   ```

5. Open your browser and visit `http://localhost:4321` to see the website.

## 🏗️ Project Structure

```
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   ├── ArticleCard.astro
│   │   ├── ArticleGrid.astro
│   │   ├── FeaturedArticle.astro
│   │   ├── Footer.astro
│   │   └── Header.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
├── package.json
└── tsconfig.json
```

## 🚀 Building for Production

To create a production-ready build, run:

```
npm run build
```

This will generate static files in the `dist/` directory, which can be deployed to any static hosting service.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/yourusername/science-news-magazine/issues).

## 📝 License

This project is [MIT](https://choosealicense.com/licenses/mit/) licensed.

## 👥 Authors

- Your Name - Initial work - [YourGitHubUsername](https://github.com/YourGitHubUsername)

## 🙏 Acknowledgments

- [Astro Documentation](https://docs.astro.build)
- [Font Sources: Google Fonts](https://fonts.google.com/)