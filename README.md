# Personal Website

A multilingual personal portfolio website built with Hugo and the Blowfish theme.

## Features

- **Multilingual Support**: English and Vietnamese content
- **Responsive Design**: Mobile-friendly layout
- **Project Portfolio**: Showcase of personal projects
- **Skills & Resume**: Professional information display
- **Contact Form**: Easy way to get in touch

## Tech Stack

- **Framework**: Hugo (Static Site Generator)
- **Theme**: Blowfish
- **Deployment**: GitHub Pages
- **Languages**: English, Vietnamese

## Project Structure

```
content/
├── en/          # English content
│   ├── projects/
│   ├── about.en.md
│   ├── skills.en.md
│   └── ...
└── vi/          # Vietnamese content
    ├── projects/
    ├── about.vi.md
    ├── skills.vi.md
    └── ...
```

## Development

### Prerequisites

- Hugo (extended version)
- Git

### Local Development

```bash
# Clone the repository
git clone <repository-url>
cd Personal-Website

# Initialize submodules (for theme)
git submodule update --init --recursive

# Start development server
hugo server -D

# Build for production
hugo
```

### Adding Content

- English content: Add to `content/en/`
- Vietnamese content: Add to `content/vi/`
- Projects: Add to respective `projects/` folders

## Deployment

Automatically deployed to GitHub Pages via GitHub Actions when pushing to main branch.

## Live Site

Visit: [https://suba-server.org](https://suba-server.org)