# Portfolio Images Directory

## Purpose
This directory stores static image assets for a portfolio website, including profile photos and gallery images.

## Directory Structure
- `profile.png` - Main profile/avatar image used across the portfolio
- `gallery/` - Directory for portfolio project screenshots and gallery images

## Asset Management Guidelines

### Image Organization
- Profile images go in the root of this directory
- Project/portfolio images belong in the `gallery/` subdirectory
- Use descriptive, kebab-case filenames (e.g., `project-dashboard.png`, `mobile-app-screenshot.jpg`)

### Image Optimization
When adding new images:
- Compress images before committing to reduce file size
- Use WebP format for better compression where browser support allows
- Keep dimensions reasonable (profile: ~500px, gallery: ~1200px max width)
- Consider providing multiple resolutions for responsive images

### Naming Conventions
- Profile images: `profile.{ext}`, `profile-{variant}.{ext}` (e.g., `profile-small.png`)
- Gallery images: `{project-name}-{description}.{ext}` (e.g., `ecommerce-homepage.jpg`)

### Common Tasks
Adding a new gallery image:
1. Optimize the image file
2. Save to `gallery/` with a descriptive name
3. Update the parent portfolio project to reference the new image path

Updating profile image:
1. Replace `profile.png` or add a variant with suffix
2. Ensure referenced path in portfolio matches filename
