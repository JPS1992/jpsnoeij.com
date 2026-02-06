# Jan Pieter Snoeij - Personal Website

A minimalist personal website with light/dark mode.

## Setup

1. Add your photo as `profile.jpg` in this folder
2. Deploy to Netlify, Vercel, or GitHub Pages

## Deployment (Netlify)

1. Push this folder to a GitHub repository
2. Go to [netlify.com](https://netlify.com) and sign in with GitHub
3. Click "Add new site" → "Import an existing project"
4. Select your repository
5. Deploy settings: leave defaults (no build command needed)
6. Click "Deploy"

## Custom Domain

After deployment:
1. Go to Site settings → Domain management
2. Add your custom domain (e.g., janpietersnoeij.com)
3. Follow DNS instructions from your domain registrar

## Files

- `index.html` - Main website (includes CSS and JS inline)
- `profile.jpg` - Your profile photo (you need to add this)

## Customization

Edit `index.html` to:
- Update bio text (search for `class="about"`)
- Add/remove publications (search for `class="pub-list"`)
- Change colors (CSS variables at the top in `:root`)
- Update social links (search for `hero-social`)
