# Romantic Flower Project

[![Netlify Status](https://api.netlify.com/api/v1/badges/YOUR_SITE_ID/deploy-status.svg)](https://app.netlify.com/sites/YOUR_SITE_NAME/deploys)

**Romantic-Flower-Project** is a visually captivating web project that blends floral animations with a romantic color palette. This project aims to create a serene, elegant atmosphere with SVG animations and CSS styling, making it ideal for personal websites, portfolios, or any romantic-themed content.

🌸 **[Live Demo](https://romantic-flowers.netlify.app/)** (Replace with your actual Netlify URL)

## Features

- Beautiful floral SVG animations
- Romantic and soft color palette
- Interactive animations with hover effects
- Simple, elegant design perfect for romantic or personal websites

## Technologies Used

- HTML
- CSS
- SVG Animations

## How to Use

### Local Development

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/Nipuna-Lakruwan/romantic-flower-project.git
   ```

2. Open the project directory:

   ```bash
   cd romantic-flower-project
   ```

3. Open `index.html` in your web browser to view the project, or use a local server:

   ```bash
   # Using Node.js http-server
   npm install
   npm start

   # Or using Python
   python -m http.server 3000

   # Or using live-server for development
   npm run dev
   ```

### Deploy to Netlify

This project is ready for Netlify deployment:

#### Option 1: Drag & Drop

1. Build your project (if needed) - this project is already production-ready
2. Drag and drop the entire project folder to [Netlify Deploy](https://app.netlify.com/drop)

#### Option 2: Git Integration

1. Push your code to a Git repository (GitHub, GitLab, or Bitbucket)
2. Connect your repository to [Netlify](https://app.netlify.com)
3. Configure build settings:
   - Build command: (leave empty for static sites)
   - Publish directory: `.` (root directory)
4. Deploy!

#### Option 3: Netlify CLI

```bash
# Install Netlify CLI
npm install -g netlify-cli

# Login to Netlify
netlify login

# Deploy from project directory
netlify deploy

# Deploy to production
netlify deploy --prod
```

The project includes a `netlify.toml` configuration file for optimal deployment settings.

## Customization

- **Colors**: You can modify the colors of the flowers and background in the `styles.css` file to suit your preferences.
- **Animations**: To adjust the animation speed or behavior, tweak the CSS properties under the `.flower-animation` class or any related animation classes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

Created by Nipuna Lakruwan

Feel free to contribute, open pull requests, or contact me for any queries!
