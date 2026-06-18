# Advanced Handyman Course

A comprehensive interactive course designed to teach advanced handyman skills through an engaging web application.

## Features

- **Progressive Learning**: Structured lessons with clear progression
- **Interactive Interface**: Hands-on learning experience
- **Mobile Responsive**: Works seamlessly on desktop, tablet, and mobile devices
- **PWA Support**: Installable as a progressive web app for offline access

## Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- For local development, a simple HTTP server

### Local Development

To run locally, use a simple HTTP server:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (http-server)
npx http-server
```

Then visit `http://localhost:8000` in your browser.

## Project Structure

```
.
├── index.html          # Main application entry point
├── manifest.json       # PWA manifest configuration
├── icon.svg           # App icon for PWA
├── .gitignore         # Git ignore rules
├── README.md          # This file
└── vercel.json        # Vercel deployment configuration
```

## Deployment

### Vercel

This project is optimized for deployment on Vercel:

1. Push your code to a Git repository (GitHub, GitLab, or Bitbucket)
2. Visit [vercel.com](https://vercel.com) and connect your repository
3. Vercel will automatically deploy your changes

### Other Platforms

This is a static site and can be deployed to:
- GitHub Pages
- Netlify
- AWS S3 + CloudFront
- Any static hosting service

## License

[Add your license information here]

## Contributing

[Add contribution guidelines if applicable]
