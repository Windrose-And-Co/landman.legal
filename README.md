# Landman Legal - Frontend

## Overview
Landman Legal is the frontend implementation for the tax law office of Nathaniel Landman, L.L.C. This repository contains the static website files and assets needed to deploy the firm's online presence, including interactive elements such as a Google Maps integration, a consultation booking system, and optimized styling using CSS and JavaScript.

## Tech Stack
- **HTML** (Structure)
- **CSS** (Styling, Responsive Design)
- **JavaScript** (Client-side functionality)
- **Parcel** (Bundling and Asset Optimization)
- **PurgeCSS** (CSS Optimization)

## Features
- Secure API key handling for Google Maps integration
- Optimized performance using PurgeCSS
- Mobile-responsive design with modern UI elements
- Automated deployment configuration via `_redirects`
- Environment variable support using Parcel

## Setup Instructions

### Prerequisites
- Node.js (LTS recommended)
- NPM (installed with Node.js)

### Installation
Clone the repository:
```sh
git clone https://github.com/Windrose-And-Co/landman.legal.git
cd landman.legal
```

Install dependencies:
```sh
npm install
```

### Running Locally
Start the local development server:
```sh
npm run serve
```
This will launch the project at `http://localhost:1234/`.

### Building for Production
To generate an optimized production build, run:
```sh
npm run parcel-build
```
The output will be in the `dist/` directory.

## Environment Variables
Create a `.env` file in the project root and add your Google Maps API key:
```sh
GOOGLE_MAPS_API_KEY=your-api-key-here
```
Ensure the `.env` file is added to `.gitignore` to prevent exposure.

## Deployment
This project is configured for static hosting and supports automatic redirects via `_redirects`.

## Contributing
1. Fork the repository
2. Create a new branch (`feature-new-component`)
3. Commit changes
4. Open a Pull Request

## License
This project is proprietary and maintained by Windrose & Co.

---
**Contact:** [Windrose & Co](https://windroseandco.com)

