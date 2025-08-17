# PickleLabs Website

A Jekyll-based website for PickleLabs, featuring gear reviews, training plans, videos, and insights from a Vatic Pro, Hesacore, and Ronbus ambassador.

## Features

- **Gear Reviews**: Honest, in-depth reviews of pickleball equipment
- **Training Plans**: Comprehensive training programs for all skill levels
- **Video Content**: Instructional videos, reviews, and tournament highlights
- **Brand Ambassador**: Official ambassador for Vatic Pro, Hesacore, and Ronbus
- **Responsive Design**: Built with Bootstrap 5 for mobile-friendly experience
- **SEO Optimized**: Built-in SEO features and meta tags

## Technology Stack

- **Jekyll**: Static site generator
- **Bootstrap 5**: Frontend framework
- **GitHub Pages**: Hosting platform
- **Bootstrap Icons**: Icon library

## Local Development

### Prerequisites

- Ruby (version 2.6 or higher)
- RubyGems
- Bundler

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/picklelabs-website.git
   cd picklelabs-website
   ```

2. Install dependencies:
   ```bash
   bundle install
   ```

3. Start the development server:
   ```bash
   bundle exec jekyll serve
   ```

4. Open your browser and navigate to `http://localhost:4000`

### Building for Production

```bash
bundle exec jekyll build
```

The built site will be in the `_site` directory.

## Project Structure

```
picklelabs-website/
├── _config.yml          # Jekyll configuration
├── _layouts/            # Layout templates
│   └── default.html     # Main layout
├── _reviews/            # Gear review posts
├── assets/              # Static assets
│   └── images/          # Images including logo
├── index.html           # Homepage
├── about.html           # About page
├── reviews.html         # Reviews index
├── training.html        # Training plans
├── videos.html          # Video content
├── terms.html           # Terms and privacy
├── 404.html            # 404 error page
├── Gemfile             # Ruby dependencies
└── README.md           # This file
```

## Content Management

### Adding Reviews

1. Create a new markdown file in the `_reviews/` directory
2. Use the following front matter structure:

```yaml
---
layout: review
title: "Product Name Review"
description: "Brief description of the review"
date: YYYY-MM-DD
author: PickleLabs Ambassador
brand: Brand Name
model: Model Name
category: Category
rating: 4.5
price: "$XXX.XX"
sponsored: true/false
tags: [tag1, tag2, tag3]
---
```

### Adding Training Plans

1. Create a new markdown file in the `_training/` directory
2. Use appropriate front matter for training content

### Adding Videos

1. Create a new markdown file in the `_videos/` directory
2. Include video embed codes and descriptions

## Brand Ambassador Information

This website represents official ambassador relationships with:

- **Vatic Pro**: Premium pickleball paddles and gear
- **Hesacore**: Revolutionary grip technology
- **Ronbus**: Innovative training equipment

All sponsored content is clearly marked with disclosure badges and detailed in the Terms & Privacy page.

## Deployment

This site is configured for GitHub Pages deployment. Simply push changes to the main branch and GitHub Pages will automatically build and deploy the site.

### Custom Domain

The site is configured to use the custom domain `picklelabs.ai` via the `CNAME` file.

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test locally
5. Submit a pull request

## License

This project is proprietary and confidential. All rights reserved.

## Contact

- **Email**: info@picklelabs.ai
- **Website**: picklelabs.ai
- **Social Media**: @picklelabs

---

Built with ❤️ for the pickleball community