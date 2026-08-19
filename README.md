# Invincible Ink Website

This is a static website built with Astro, React, and Tailwind CSS.

## Getting Started

1. Install dependencies:
   ```bash
   npm install
   ```

2. Run the development server:
   ```bash
   npm run dev
   ```

## Deployment to Netlify

To deploy this site on Netlify from GitHub:

1. Create a repository on GitHub and push this code.
   ```bash
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/yourusername/your-repo.git
   git push -u origin main
   ```

2. Go to [Netlify](https://app.netlify.com/) and log in.
3. Click "Add new site" -> "Import an existing project".
4. Select GitHub and authorize Netlify.
5. Choose your newly created repository.
6. Netlify will automatically detect that this is an Astro project. The build settings should be:
   - **Build command:** `npm run build`
   - **Publish directory:** `dist`
7. Click "Deploy site".

Netlify will automatically build and deploy your site every time you push to the `main` branch.
