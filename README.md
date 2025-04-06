<h1 align=center>Hugo Dark Noir | <a href="https://pranamshetty.dev" rel="nofollow">Demo</a></h1>

<h4 align=center>🌑 Dark | 🔍 Minimalist | 📱 Responsive | ⚡ Fast</h4>
<br>

> Dark Noir is a clean, minimalistic theme for Hugo with a focus on readability and simplicity.

[![Minimum Hugo Version](https://img.shields.io/static/v1?label=min-HUGO-version&message=>=v0.92.0&color=blue&logo=hugo)](https://github.com/gohugoio/hugo/releases/tag/v0.92.0)
[![GitHub](https://img.shields.io/github/license/prxshetty/hugo-noir)](https://github.com/prxshetty/hugo-noir/blob/main/LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/prxshetty/hugo-noir?style=social)](https://github.com/prxshetty/hugo-noir/stargazers)
[![Hugo Themes](https://img.shields.io/badge/Hugo--Themes-@Dark_Noir-blue)](https://themes.gohugo.io/themes/hugo-noir/)

---

## Screenshots 📸

<p align="center">
  <kbd><img src="https://raw.githubusercontent.com/prxshetty/hugo-noir/main/images/screenshot.png" alt="Dark Noir Theme Screenshot" title="Dark Noir"/></kbd>
</p>

<p align="center">
  <em>Homepage view with minimalist design and dark mode</em>
</p>

<p align="center">
  <kbd><img src="https://raw.githubusercontent.com/prxshetty/hugo-noir/main/images/tn.png" alt="Dark Noir Theme Thumbnail" title="Dark Noir Thumbnail"/></kbd>
</p>

<p align="center">
  <em>Blog post view with optimal readability</em>
</p>

<p align="center">
  <kbd><img src="https://raw.githubusercontent.com/prxshetty/hugo-noir/main/images/contact.png" alt="Contact Page" title="Contact Page"/></kbd>
</p>

<p align="center">
  <em>Contact page with social media links and clean layout</em>
</p>

<p align="center">
  <kbd><img src="https://raw.githubusercontent.com/prxshetty/hugo-noir/main/images/experience.png" alt="Experience Page" title="Experience Page"/></kbd>
</p>

<p align="center">
  <em>Experience page showcasing professional background with statistics</em>
</p>

<p align="center">
  <kbd><img src="https://raw.githubusercontent.com/prxshetty/hugo-noir/main/images/project.png" alt="Projects Page" title="Projects Page"/></kbd>
</p>

<p align="center">
  <em>Projects page displaying work with technology tags and descriptions</em>
</p>

<p align="center">
  <kbd><img src="https://raw.githubusercontent.com/prxshetty/hugo-noir/main/images/blogs.png" alt="Blogs Page" title="Blogs Page"/></kbd>
</p>

<p align="center">
  <em>Blogs page displaying blogs with tags and a short descriptions</em>
</p>

---

## Features 💥

- **Clean Design**: Minimalist aesthetic for distraction-free reading
- **Responsive Layout**: Perfect viewing experience across all devices
- **Dark Mode Support**: Easy on the eyes, especially in low-light environments
- **Tailwind CSS**: Modern utility-first CSS framework for styling
- **Fast Performance**: Optimized for speed with minimal JavaScript
- **SEO-Friendly**: Built with search engines in mind, including Open Graph tags
- **Blog-Ready**: Perfect for personal blogs and portfolios
- **No Dependencies**: No webpack, nodejs or other dependencies required to edit the theme
- **Social Icons**: Easy configuration for social media links
- **Custom Styling**: Simple customization through CSS variables
- **Featured Content**: Support for featured posts on the homepage
- **Tech Stack Carousel**: Showcase your skills with a smooth, interactive tech stack carousel
- **Single Page Portfolio**: Everything in one place - about, experience, projects, and contact sections
- **Inline SVGs**: Uses inline SVG icons for faster loading and better performance
- **Mobile-First Design**: Fully optimized for mobile devices with touch-friendly interactions
- **Local Clock**: Real-time clock display using minimal JavaScript for accurate time

---

## Install/Update 📥

### Option 1: Clone Repository

```bash
# From your Hugo site directory
git clone https://github.com/prxshetty/hugo-noir themes/hugo-noir
```

### Option 2: Add as a Git Submodule

```bash
# From your Hugo site directory
git submodule add https://github.com/prxshetty/hugo-noir themes/hugo-noir
```

Then, add the following to your site's `config.toml`:

```toml
theme = "hugo-noir"
```

---

## Requirements ⚙️

- Hugo Extended version
- Minimum version: 0.92.0

---

## Configuration ⚙️

This theme supports a variety of configuration options in your `hugo.toml` (or `config.toml`) file. An example `hugo.toml` configuration can be found in `exampleSite/hugo.toml`. Below is an example configuration with explanations:

### Basic Configuration

```toml
baseURL = "https://example.com"
languageCode = 'en-us'
title = 'Your Name'
theme = 'hugo-noir'

# URL handling
relativeURLs = true
canonifyURLs = true

# Taxonomy configuration
[taxonomies]
  category = "categories"
  tag = "tags"
```

### Personal Information

```toml
[params]
name = "Your Name"
location = "City, Country"
description = "Your bio goes here..."
profile_image = "/images/profile.jpg"

# Social Media Links
github = "https://github.com/yourusername"
email = "your.email@example.com"
twitter = "https://twitter.com/yourusername"
linkedin = "https://linkedin.com/in/yourusername"
instagram = "https://instagram.com/yourusername"
```

### Social Icons

You can configure social icons that appear in the footer:

```toml
[params.socialIcons]
github = "https://github.com/yourusername"
twitter = "https://twitter.com/yourusername"
linkedin = "https://linkedin.com/in/yourusername"
instagram = "https://instagram.com/yourusername"
email = "mailto:your.email@example.com"
```

### Experience Section

```toml
[[params.experience]]
company = "Company Name"
role = "Your Role"
period = "Jan 2023 - Present"
logo = "/images/company/logo.png"
description = "Brief description of your role and responsibilities."
responsibilities = [
    "Responsibility 1 with specific achievements",
    "Responsibility 2 with specific achievements",
    "Responsibility 3 with specific achievements"
]

# For open source contributions
[[params.experience]]
company = "GitHub"
role = "Open Source Contributor"
period = "Jan 2023 - Present"
description = "Contributing to open source projects"
github_username = "yourusername"
```

### Projects Section

```toml
[[params.projects]]
title = "Project Name"
description = "Brief description of the project and what it does."
tech = "Technologies used (e.g., Python, React, TensorFlow)"
image = "/images/projects/project.png"
link = "https://github.com/yourusername/project"
```

### Blog Posts

```toml
[[params.blogs]]
title = "Blog Post Title"
date = "2023-01-15"
summary = "Brief summary of what the blog post is about."
tags = ["tag1", "tag2", "tag3"]
content = """
Short excerpt or introduction to the blog post...
"""
link = "https://yourblog.com/post-url"
```

### Featured Content

You can mark certain content as featured to display it prominently on the homepage:

```toml
[[params.blogs]]
title = "Featured Blog Post"
date = "2023-01-15"
summary = "This post will be featured on the homepage."
tags = ["tag1", "tag2", "tag3"]
featured = true
link = "https://yourblog.com/featured-post"
```

### Navigation Menu

```toml
[menu]
  [[menu.main]]
    name = "About"
    url = "/about/"
    weight = 1
  [[menu.main]]
    name = "Experience"
    url = "/experience/"
    weight = 2
  [[menu.main]]
    name = "Projects"
    url = "/projects/"
    weight = 3
  [[menu.main]]
    name = "Blogs"
    url = "/blogs/"
    weight = 4
  [[menu.main]]
    name = "Contact"
    url = "/contact/"
    weight = 5
```

---

## Content Structure 📁

The theme expects the following content structure:

```
content/
├── _index.md          # Homepage content
├── about.md           # About page
├── experience.md      # Experience page
├── projects.md        # Projects page
├── blog.md            # Blogs Page
└── contact.md         # Contact page
```

Each page can use front matter to customize its appearance and behavior.

---

## Front Matter Examples 📝

### Blog Post

```yaml
---
title: "My First Post"
date: 2023-03-15T10:30:00+05:30
draft: false
tags: ["hugo", "web development"]
categories: ["tutorials"]
description: "A detailed description of the post for SEO and previews"
featured_image: "/images/post-cover.jpg"
featured: false  # Set to true to feature this post on the homepage
---
```

### Static Page

```yaml
---
title: "About Me"
date: 2023-03-15T10:30:00+05:30
draft: false
menu: "main"
description: "Learn more about me and my background"
---
```

---

## Customization 🎨

### Custom CSS

You can customize the theme by modifying the following files:

- `assets/css/custom.css`: Add your custom CSS styles here
- `assets/css/variables.css`: Modify theme variables like colors and fonts

## Custom Icons

You can add custom icons to your site by using SVG icons. SVGs are preferred because they're lightweight, scalable, and render crisply on all devices without losing quality.

You can find free SVG icons at these popular sites:
- [Font Awesome](https://fontawesome.com/)
- [Feather Icons](https://feathericons.com/)
- [Heroicons](https://heroicons.com/)
- [Simple Icons](https://simpleicons.org/) (great for brand/tech stack icons)
- [Devicon](https://devicon.dev/) (specifically for programming languages and tools)

I included it inline in the HTML for better performance and speed. 

Example of custom CSS:

```css
/* assets/css/custom.css */
.site-header {
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.post-title {
  font-size: 2.5rem;
  color: var(--primary-color);
}
```


Example:

```javascript
// assets/js/custom.js
document.addEventListener('DOMContentLoaded', function() {
  console.log('Custom JavaScript loaded');
  
  // Your custom code here
});
```

### HTML Templates

For more advanced customization, you can override the theme's templates by creating your own versions in your site's `layouts` directory:

- `layouts/_default/single.html`: Override the default single page template
- `layouts/_default/list.html`: Override the default list template
- `layouts/partials/header.html`: Override the header partial

---

## FAQs 🙋

Coming soon...

---

## Performance ⚡

Dark Noir is designed with performance in mind, ensuring fast loading times and a smooth user experience.

---

## Support 🫶

- Star 🌟 this repository
- Share it with others who might find it useful
- Report issues or suggest improvements

---

## Special Thanks 🌟

- [Hugo](https://gohugo.io/)
- [Tailwind CSS](https://tailwindcss.com/)
- All contributors and supporters

---

## License 📄

This theme is released under the [MIT License](https://github.com/prxshetty/hugo-noir/blob/main/LICENSE). 

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/prxshetty/hugo-noir/blob/main/LICENSE) 