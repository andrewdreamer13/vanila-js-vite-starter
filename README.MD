# Static Sites Vite Starter 🚀

A professional, modular starter kit for building high-performance static websites. This boilerplate is designed to automate routine tasks and keep your project architecture clean.

##  Key Features

- **Modular HTML**: Organise your code using HTML partials for a component-based workflow.
- **Modern CSS**: Pre-configured **SCSS** structure with a clean reset system and efficient build process.
- **Smart Asset Optimization**: 
  - Automated conversion of images to **WebP** format.
  - Automated font conversion to **Woff2**.
- **Performance First**: Optimized for speed and high Lighthouse scores right out of the box.
- **Clean Git History**: Pre-configured `.gitignore` to keep your repository free of build artifacts and archives.

## 🛠 Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/andrewdreamer13/static-sites-vite-starter.git](https://github.com/andrewdreamer13/static-sites-vite-starter.git)

2. **Reset Git History (For a new project):**
If you are using this starter as a template for a new project, run these commands to start a fresh history:
rm -rf .git
git init

3. **Install dependencies:**
npm install

4. **Configure package.json:**
Open the file and update the "name" field with your project title (use lowercase and hyphens, e.g., "my-project").

5.**Start Development Server:**
npm run dev

**Production Commands:**
npm run build — Bundles the project into the dist folder with optimized assets and image compression.

npm run preview — Locally previews the production build to check performance before deployment.