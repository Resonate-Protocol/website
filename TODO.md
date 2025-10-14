# Resonate Website TODO

## High Priority

### Content

- [ ] **Homepage Content** (`src/index.html`)
  - [ ] Write main tagline for Resonate Protocol
  - [ ] Write introduction paragraph explaining what Resonate is
  - [ ] Add key features section
  - [ ] Explain how it works (basic workflow)
  - [ ] Document use cases and applications
  - [ ] Add "Adopted by / Example Projects" section with project logos
  - [ ] Detail the problem Resonate solves
  - [ ] Define scope and constraints

- [ ] **Protocol Specification** (`src/spec.md`)
  - [ ] Write protocol overview and architecture
  - [ ] Document communication protocols and message formats
  - [ ] Create API specifications
  - [ ] Add implementation guidelines
  - [ ] Document security considerations
  - [ ] Add code examples

- [ ] **Code Page** (`src/code.md`)
  - [ ] Add Music Assistant GitHub URL (replace TODO on line 20)
  - [ ] Add example projects section
  - [ ] Add code snippets and usage examples
  - [ ] Document integration steps
  - [ ] Add troubleshooting guide

### Assets

- [ ] **Images** (`public/images/`)
  - [ ] Add Resonate logo (SVG preferred, or PNG)
    - Suggested filename: `resonate-logo.svg`
    - Update reference in `src/_includes/base.html:60`
  - [ ] Add favicon
    - Filename: `resonate-favicon.png`
    - Size: 32x32px or 64x64px
  - [ ] Add social media preview image
    - Filename: `social.png`
    - Recommended size: 1200x630px
  - [ ] Remove placeholder.txt file once images are added

### GitHub Setup

- [ ] **Repository Configuration**
  - [ ] Create GitHub repository (if not exists)
  - [ ] Push code to main branch
  - [ ] Enable GitHub Pages in repository settings
    - Go to Settings → Pages
    - Set source to "GitHub Actions"
  - [ ] Verify deployment workflow runs successfully
  - [ ] Test deployed site

## Medium Priority

### Branding & Design

- [ ] **Color Scheme**
  - [ ] Review and update link color in `public/style.css` (currently #03a9f4)
  - [ ] Define primary/secondary colors
  - [ ] Update active menu item underline color if needed

- [ ] **Typography**
  - [ ] Review font choices
  - [ ] Adjust heading sizes if needed

- [ ] **Footer**
  - [ ] Add contact information (if applicable)
  - [ ] Add social media links (if applicable)
  - [ ] Add copyright/license information

### Documentation

- [ ] **README.md**
  - [ ] Add license information
  - [ ] Add contributing guidelines
  - [ ] Add badge for deployment status

- [ ] **Project Information**
  - [ ] Add LICENSE file
  - [ ] Add CONTRIBUTING.md (if accepting contributions)
  - [ ] Add CODE_OF_CONDUCT.md (if applicable)

### SEO & Meta

- [ ] Review and update meta descriptions for all pages
- [ ] Add keywords meta tags (if needed)
- [ ] Create sitemap.xml
- [ ] Add robots.txt
- [ ] Update OpenGraph URLs once domain is finalized

## Low Priority

### Enhancements

- [ ] Add search functionality (if needed)
- [ ] Add analytics (Google Analytics, Plausible, etc.)
- [ ] Add newsletter signup (if applicable)
- [ ] Add blog section (if needed)
- [ ] Add dark mode toggle (if desired)
- [ ] Add syntax highlighting for code blocks
- [ ] Add copy-to-clipboard buttons for code snippets

### Testing

- [ ] Test on different browsers (Chrome, Firefox, Safari, Edge)
- [ ] Test on mobile devices
- [ ] Check all internal links work
- [ ] Validate HTML
- [ ] Check accessibility (WCAG compliance)
- [ ] Test page load speed

### Future Considerations

- [ ] Add multilingual support (if needed)
- [ ] Create API documentation section (if separate from spec)
- [ ] Add changelog page
- [ ] Add FAQ section
- [ ] Create interactive demos/examples
- [ ] Add community/forum links

## Current Blockers

- **Music Assistant GitHub URL** - Needed for `src/code.md`

## Notes

- Site built with Eleventy 2.0.1
- Deploys automatically via GitHub Actions when pushed to main
- Local development: `./script/develop` (runs on port 5005)
- Production build: `./script/build`
