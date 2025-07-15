# Al Omar Hajj and Umrah Services Website

## Summary
A responsive website for Al Omar Hajj and Umrah Services built using HTML and Tailwind CSS. The website showcases the company's services, packages, and contact information for potential customers seeking Hajj and Umrah travel services.

## Structure
- **HTML Files**: Core website pages (index.html, aboutus.html, Services.html, packages.html, contact_new.html)
- **images/**: Directory containing website images and assets
- **.vscode/**: Editor configuration including Tailwind CSS settings
- **node_modules/**: Dependencies installed via npm

## Language & Runtime
**Language**: HTML, CSS, JavaScript
**Framework**: Tailwind CSS
**Package Manager**: npm

## Dependencies
**Main Dependencies**:
- **fluid-tailwind**: ^1.0.4 (Development dependency)

**CDN Dependencies**:
- **Tailwind CSS**: Loaded via CDN (https://cdn.tailwindcss.com)
- **Boxicons**: CSS icon library (https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css)
- **Instagram Embed**: Script for embedding Instagram content

## Build & Installation
```bash
# Install dependencies
npm install
```

## Tailwind Configuration
**Configuration File**: .vscode/tailwind.config.js
**Custom Theme**:
- Custom font family: 'poppins'
- Extended theme configuration in HTML files using inline Tailwind config

## Website Components
**Pages**:
- **index.html**: Main landing page
- **aboutus.html**: Company information
- **Services.html**: Service offerings
- **packages.html**: Hajj and Umrah packages
- **contact_new.html**: Contact information
- **servicecard1.html**: Individual service details

**Features**:
- Responsive design for mobile and desktop
- Custom animations and hover effects
- Floating contact buttons (phone and WhatsApp)
- Image gallery with modal viewer
- Instagram feed integration
- Google Reviews section
- FAQ accordion section

## CSS Implementation
**Approach**: Mix of Tailwind utility classes and custom CSS
**Custom Styles**:
- Floating contact buttons with animations
- Package card hover effects
- Review panel hover effects
- Navbar transitions
- Mobile menu animations
- Gallery and modal implementations

## JavaScript Functionality
- Mobile menu toggle
- FAQ accordion functionality
- Image gallery modal
- Navbar scroll effects
- Instagram embed integration
