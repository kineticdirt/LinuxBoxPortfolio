# Abhinav Allam - Portfolio

Full portfolio website showcasing AI/ML projects, software engineering skills, and professional experience.

## Live Site

**Main Portfolio**: https://abhinavall.net (via GitHub Pages)

## Features

- ✨ Modern, responsive design
- 🎨 Dark mode interface
- 📱 Mobile-friendly
- 🚀 Fast loading with optimized assets
- 📊 Interactive project showcases
- 💼 Professional experience timeline
- 🛠️ Technical skills display
- 📧 Contact form
- 📄 Resume/CV downloads

## Tech Stack

- **Frontend**: HTML5, CSS3, Vanilla JavaScript (ES6+)
- **Backend API**: Express.js, Node.js
- **Deployment**: GitHub Pages
- **Testing**: Jest
- **Linting**: ESLint, Stylelint

## Setup for Development

```bash
# Install dependencies
npm install

# Run development server
npm run dev

# Run tests
npm test

# Build and validate
npm run build
```

## Deployment

This repository is automatically deployed to GitHub Pages from the `gh-pages` branch.

### GitHub Pages Configuration

1. Repository Settings → Pages
2. Source: Deploy from a branch
3. Branch: `gh-pages` / root
4. Save

### Custom Domain (abhinavall.net)

To point your custom domain to this GitHub Pages site:

1. Add a `CNAME` file to the repository root with your domain:
   ```
   abhinavall.net
   ```

2. In your domain registrar (Cloudflare DNS):
   - Add CNAME record: `abhinavall.net` → `kineticdirt.github.io`
   - Or A records pointing to GitHub Pages IPs:
     - `185.199.108.153`
     - `185.199.109.153`
     - `185.199.110.153`
     - `185.199.111.153`

3. Wait for DNS propagation (can take up to 24 hours)

## Project Structure

```
LinuxBoxPortfolio/
├── index.html              # Main HTML file
├── styles.css              # Main stylesheet
├── script.js               # Client-side JavaScript
├── assets/
│   ├── images/             # Image assets
│   └── documents/          # Resume PDFs
├── api/                    # Backend API (optional)
├── package.json            # Dependencies
└── README.md              # This file
```

## Author

**Abhinav Allam**
- Email: abhinav.allam@abhinavall.net
- GitHub: [@kineticdirt](https://github.com/kineticdirt)
- LinkedIn: [Abhinav Allam](https://www.linkedin.com/in/abhinav-allam-2a72821b9/)

## License

MIT License - feel free to use this as a template for your own portfolio!

