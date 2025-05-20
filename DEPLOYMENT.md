# Taylor Series Visualizer - Deployment Guide

This package contains a production-ready build of the Taylor Series Visualizer web application. The application is a static website that can be deployed to any web hosting service that supports static sites.

## Contents

- `index.html`: The main HTML file
- `assets/`: Directory containing all JavaScript, CSS, and font files
- `vite.svg`: Application icon
- `README.md`: Project information

## Deployment Instructions

### Option 1: Deploy to a Static Web Hosting Service

1. Upload all files and folders in this package to your web hosting service
2. Ensure the directory structure is maintained
3. Point your domain to the directory containing these files

Popular static hosting services include:
- GitHub Pages
- Netlify
- Vercel
- Amazon S3
- Firebase Hosting

### Option 2: Serve Locally

You can also serve these files locally using a simple HTTP server:

```bash
# Using Python
python -m http.server

# Using Node.js
npx serve
```

Then access the application at http://localhost:8000 or the port specified by your server.

## Troubleshooting

If you encounter any issues with the deployment:
- Ensure all files are uploaded with the correct directory structure
- Check that your web server is configured to serve index.html for the root path
- Verify that your hosting service supports single-page applications if you're using client-side routing

For any additional questions or support, please refer to the README.md file for project information.
