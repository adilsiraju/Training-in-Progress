# TIP - Training in Progress 🚀

> Mohammed Adil Siraju's AI/ML Learning Journey Blog

A clean, minimal blog built with [Quarto](https://quarto.org/) to document my learning journey in **Artificial Intelligence**, **Machine Learning**, and **Deep Learning**. This repository serves as both a learning log and a portfolio showcase.

## ✨ Features

- **📱 Responsive Design** - Mobile-first approach with clean aesthetics
- **🎨 Custom Styling** - Minimal design leveraging Pulse theme
- **📝 Blog Posts** - Technical insights and project documentation
- **🖼️ Hero Image** - Engaging visual presentation
- **⚡ Fast Loading** - Optimized static site generation
- **🔍 SEO Friendly** - Built-in metadata and search optimization

## 🚀 Live Site

Visit the live blog: [https://adilsiraju.github.io/Training-in-Progress/](https://adilsiraju.github.io/Training-in-Progress/)

## 📁 Project Structure

```
├── README.md               # Project documentation
├── _quarto.yml            # Quarto configuration
├── index.qmd              # Homepage content
├── about.qmd              # About page
├── styles.css             # Custom CSS styles
├── hero-theme.scss        # Hero section styling
├── hero.png               # Hero image
├── profile.jpg            # Profile image
├── posts/                 # Blog posts directory
│   ├── welcome/           # Welcome post
│   └── post-with-code/    # FastAI learning post
├── chapters/              # Learning chapters (Jupyter notebooks)
│   ├── python/            # Python fundamentals
│   ├── fastai/            # FastAI course content
│   ├── computer-vision/   # Computer vision projects
│   └── mlops/             # MLOps and deployment
└── _site/                 # Generated site (auto-built)
```

## 🛠️ Tech Stack

- **[Quarto](https://quarto.org/)** - Static site generator
- **[Bootstrap 5](https://getbootstrap.com/)** - CSS framework (via Pulse theme)
- **SCSS** - Enhanced CSS with variables and nesting
- **GitHub Pages** - Hosting and deployment
- **GitHub Actions** - Automated CI/CD

## 📝 Content Areas

### 🏠 Homepage
- Personal introduction and mission
- Current learning focus areas
- Recent achievements showcase
- Latest blog posts listing

### 👨‍💻 About Page
- Professional background and education
- Technical skills and expertise
- Project portfolio highlights
- Certifications and achievements

### 📚 Blog Posts
- **FastAI Learning Progress** - Computer vision fundamentals
- **Welcome Post** - Journey introduction and goals
- *More posts coming as I continue learning...*

### 📖 Learning Chapters
- **Python Fundamentals** - Core concepts and best practices
- **FastAI Course** - Practical deep learning notebooks
- **Computer Vision** - Image processing and CNN implementations
- **MLOps** - Deployment and production workflows

## 🚀 Quick Start

### Prerequisites
- [Quarto CLI](https://quarto.org/docs/get-started/)
- [Git](https://git-scm.com/)

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/adilsiraju/Training-in-Progress.git
   cd Training-in-Progress
   ```

2. **Preview the site**
   ```bash
   quarto preview
   ```

3. **Build for production**
   ```bash
   quarto publish gh-pages
   ```

## 📖 Adding New Content

### Creating a New Blog Post

1. Create a new folder in `posts/`
2. Add an `index.qmd` file with frontmatter:
   ```yaml
   ---
   title: "Your Post Title"
   author: "Mohammed Adil Siraju"
   date: "2025-XX-XX"
   categories: [category1, category2]
   description: "Brief description"
   ---
   ```
3. Write your content in Markdown/Quarto format
4. Preview with `quarto preview`

### Adding Learning Chapters

1. Choose the appropriate chapter folder (`python/`, `fastai/`, `computer-vision/`, `mlops/`)
2. Create a new Jupyter notebook (`.ipynb`) or Quarto document (`.qmd`)
3. Add frontmatter at the top:
   ```yaml
   ---
   title: "Chapter Title"
   author: "Mohammed Adil Siraju"
   date: "2025-XX-XX"
   categories: [topic, subtopic]
   description: "Learning objective"
   ---
   ```
4. The chapter will automatically appear in the Chapters section

### Customizing Styles

- Edit `styles.css` for general styling
- Modify `hero-theme.scss` for hero section changes
- Update `_quarto.yml` for site configuration

## 🎯 Current Learning Focus

- **FastAI Course** - Practical deep learning approaches
- **Computer Vision** - Building on architectural style classifier
- **MLOps** - Deployment and automation pipelines
- **Technical Writing** - Documenting learning journey

## 📊 Project Highlights

- **Architectural Style Classifier** - 73% accuracy across 25 styles
- **CI/CD for ML Models** - 30% faster deployment cycles
- **Clean Blog Design** - Minimal, focused user experience

## 🤝 Connect

- **Portfolio**: [adilsiraju.vercel.app](https://www.adilsiraju.vercel.app)
- **Email**: [mohdadilsiraju@gmail.com](mailto:mohdadilsiraju@gmail.com)
- **GitHub**: [@adilsiraju](https://github.com/adilsiraju)
- **Twitter**: [@mohd3dil](https://twitter.com/mohd3dil)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

*Built with ❤️ using Quarto and hosted on GitHub Pages*

**⭐ Star this repo if you find it helpful!**