# Posts Directory

This directory contains all blog posts for the TIP (Training in Progress) blog.

## 📁 Structure

Each blog post should be in its own subdirectory with an `index.qmd` file:

```
posts/
├── _metadata.yml          # Global metadata for posts
├── welcome/               # Welcome post
│   ├── index.qmd         # Post content
│   └── thumbnail.jpg     # Featured image
└── post-with-code/       # FastAI learning post
    ├── index.qmd         # Post content
    └── image.jpg         # Featured image
```

## 📝 Creating a New Post

1. **Create a new directory** with a descriptive name (use hyphens for spaces)
2. **Add `index.qmd`** with proper frontmatter:

```yaml
---
title: "Your Post Title"
author: "Mohammed Adil Siraju"
date: "YYYY-MM-DD"
categories: [category1, category2]
image: "featured-image.jpg"  # Optional
description: "Brief description for SEO and listings"
---
```

3. **Write content** using Markdown/Quarto syntax
4. **Add images** to the same directory and reference them locally

## 🏷️ Categories

Current categories in use:
- `welcome` - Introduction and journey posts
- `learning` - Learning progress and insights
- `fastai` - FastAI course related content
- `computer-vision` - Computer vision projects and learning
- `projects` - Project showcases and documentation
- `technical` - Deep technical content and tutorials

## 📸 Images

- Place images in the same directory as the post
- Use descriptive filenames
- Optimize images for web (reasonable file sizes)
- Include alt text for accessibility

## ✨ Content Guidelines

- **Clear titles** that describe the content
- **Engaging descriptions** for better discoverability
- **Proper categorization** for organization
- **Code examples** with explanations where relevant
- **Personal insights** and learning reflections

## 🔄 Publishing

Posts are automatically included in the blog listing when:
1. They're in a subdirectory of `posts/`
2. They have an `index.qmd` file with proper frontmatter
3. The site is rebuilt (automatic on GitHub Pages)

---

*Keep documenting the learning journey! 📚*