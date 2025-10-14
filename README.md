# Resonate Protocol Website

Official website for the Resonate music experience protocol.

## Development

### Prerequisites

- Node.js (version 14 or higher)
- npm

### Setup

```bash
npm install
```

### Local Development

To run a local development server:

```bash
./script/develop
```

The site will be available at http://localhost:5005

### Build

To build the site for production:

```bash
./script/build
```

The built site will be in the `dist/` directory.

## Deployment

This site is configured to deploy automatically to GitHub Pages when changes are pushed to the `main` branch.

### GitHub Pages Setup

1. Go to your repository Settings
2. Navigate to Pages (under Code and automation)
3. Under "Build and deployment", select "GitHub Actions" as the source
4. Push to the main branch to trigger deployment

## TODO Items

### Content Updates Needed

- [ ] Add Resonate logo and favicon images to `public/images/`
- [ ] Update frontpage content in `src/index.html`
- [ ] Write protocol specification in `src/spec.md`
- [ ] Add Music Assistant GitHub URL in `src/code.md`
- [ ] Add example projects section

### Image Assets Required

- `public/images/resonate-logo.svg` (or .png) - Main logo for header
- `public/images/resonate-favicon.png` - Favicon for browser tab
- `public/images/social.png` - Social media preview image (1200x630px recommended)

## Project Structure

```
.
├── src/                    # Source files
│   ├── _includes/         # Template files
│   │   └── base.html      # Main layout template
│   ├── index.html         # Homepage
│   ├── spec.md            # Protocol specification
│   └── code.md            # Code and SDKs page
├── public/                # Static assets
│   ├── style.css          # Styles
│   └── images/            # Images and logos
├── script/                # Build scripts
│   ├── build              # Production build
│   └── develop            # Development server
├── dist/                  # Built site (generated)
└── .github/workflows/     # GitHub Actions
    └── deploy.yml         # GitHub Pages deployment
```

## Built With

- [Eleventy](https://www.11ty.dev/) - Static site generator
- GitHub Pages - Hosting

## License

TODO: Add license information
