# Nexter

A modern, responsive real estate website showcasing luxury homes and top realtors. Built with HTML, CSS, and SASS, and hosted on Firebase.

## Table of Contents

- [Description](#description)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Deployment](#deployment)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Author](#author)

## Description

Nexter is a front-end project for a real estate company, designed to provide an elegant and user-friendly experience for browsing luxury homes. The website emphasizes personal freedom and the joy of homeownership, featuring stunning visuals, detailed property listings, and information about top realtors.

## Features

- **Responsive Design**: Optimized for all devices, from mobile to desktop.
- **Luxury Homes Gallery**: Showcase of premium properties with high-quality images.
- **Top Realtors Section**: Profiles of the top-performing realtors with their sales records.
- **Story Section**: Engaging narratives about the company and its values.
- **Sidebar Navigation**: Smooth navigation with a collapsible sidebar.
- **Footer**: Comprehensive footer with links and company information.
- **Typography and Utilities**: Custom SASS mixins for consistent styling.

## Technologies Used

- **HTML5**: Semantic markup for structure.
- **CSS3**: Custom styles with advanced selectors and animations.
- **SASS**: Preprocessed CSS for modular and maintainable stylesheets.
- **Firebase Hosting**: For fast and secure web hosting.
- **Node.js**: For build tools and development server.
- **Live Server**: For local development with auto-reload.
- **Autoprefixer & PostCSS**: For CSS vendor prefixing and optimization.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/mostafaEkbal/Nexter.git
   cd Nexter
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Compile SASS** (optional, for production build):
   ```bash
   npm run build:css
   ```

## Usage

### Development

To start the development server with live reloading and SASS watching:

```bash
npm start
```

This will:
- Start a live server on `http://localhost:8080` (opens in Firefox by default).
- Watch for changes in SASS files and compile them to CSS automatically.

### Production Build

To compile and optimize CSS for production:

```bash
npm run build:css
```

This will:
- Compile SASS to CSS.
- Add vendor prefixes.
- Compress the final CSS file.

## Deployment

The project is configured for Firebase Hosting.

1. **Install Firebase CLI** (if not already installed):
   ```bash
   npm install -g firebase-tools
   ```

2. **Login to Firebase**:
   ```bash
   firebase login
   ```

3. **Deploy**:
   ```bash
   firebase deploy --only hosting
   ```

The site will be deployed to the Firebase site "nexter1".

## Project Structure

```
Nexter/
├── firebase.json          # Firebase configuration
├── package.json           # Node.js dependencies and scripts
├── public/                # Public assets (served by Firebase)
│   ├── index.html         # Main HTML file
│   ├── 404.html           # 404 error page
│   ├── css/
│   │   └── style.css      # Compiled CSS
│   └── img/               # Images and assets
├── sass/                  # SASS source files
│   ├── main.scss          # Main SASS file
│   ├── _base.scss         # Base styles
│   ├── _typography.scss   # Typography styles
│   ├── _utilities.scss    # Utility classes
│   ├── _header.scss       # Header styles
│   ├── _sidebar.scss      # Sidebar styles
│   ├── _realtors.scss     # Realtors section styles
│   ├── _homes.scss        # Homes gallery styles
│   ├── _story.scss        # Story section styles
│   ├── _gallery.scss      # Gallery styles
│   ├── _features.scss     # Features section styles
│   └── _footer.scss       # Footer styles
└── README.md              # This file
```

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature: `git checkout -b feature-name`.
3. Make your changes and commit them: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature-name`.
5. Submit a pull request.

## License

This project is licensed under the ISC License. See the [LICENSE](LICENSE) file for details.

## Author

- **Mostafa Mohamed Ekbal** - [GitHub](https://github.com/mostafaEkbal)

---

*Built with ❤️ for the love of real estate.*
