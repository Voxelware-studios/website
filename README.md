# Voxelware Studios Website

The official website for Voxelware Studios — an organization that creates Minecraft mods, plugins, and Discord bots.

## Features

- Home page with hero section, services, and featured projects
- Blog section with update posts
- Discord redirect page
- Simple dark theme with purple accents

## File Structure

```
website/
│
├── index.html                  # Home page (hero, services, featured projects)
├── style.css                   # Main styles
├── stacked-waves-haikei.svg    # Hero background
├── vxl.png                     # Logo
│
├── blogs/
│   ├── index.html              # Blog listing page
│   ├── style.css
│   ├── blog_id_1/              # Post: Website Update v1.2.0
│   │   ├── index.html
│   │   └── style.css
│   └── blog_id_2/              # Post: SmokeUtils Update v0.3.0
│       ├── index.html
│       └── style.css
│
├── projects/
│   ├── index.html              # Not built yet
│   └── style.css
│
├── contact/
│   ├── index.html              # Not built yet
│   └── style.css
│
├── discord/
│   └── index.html              # Redirects to Discord invite
│
└── api/
    └── images/                 # Project and service logos
```

## Coming Soon

- **Projects page** — list all projects with descriptions and download links
- **Contact page** — simple form (name, email, message)
- **Individual project pages** — like blog posts but for each project
- **Shared stylesheet** — one `style.css` for the whole site instead of copies in every folder

## How to Contribute

1. Fork the repo
2. Make your changes
3. Keep it consistent with the rest of the site
4. Open a pull request and describe what you changed

> Please don't use frameworks or external libraries — this site is intentionally plain HTML/CSS.
