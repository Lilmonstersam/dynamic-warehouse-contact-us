# Dynamic Warehouse Solutions - Contact Us Page

This project contains the mockup for the Dynamic Warehouse Solutions Contact Us page, rebuilt with modern Vite tooling and automated deployment to GitHub Pages.

## Tasks Completed
1. **Initialised `package.json`**: Configured scripts (`dev`, `build`, `preview`) and installed `vite` for local development.
2. **GitHub Actions**: Created `.github/workflows/deploy.yml` to automatically build and deploy to GitHub Pages upon pushing to the `main` branch.
3. **.gitignore**: Created to ensure `node_modules`, `dist`, and other unnecessary files are not committed to the repository.
4. **Vite Configuration**: Set up `vite.config.ts` with `base: '/dynamic-warehouse-contact-us/'` to ensure static assets load correctly when hosted on a GitHub Pages subpath.
5. **Documentation**: Updated this `README.md` to record the applied configurations.

## Local Development

To run this project locally:

1. Install dependencies:
   ```bash
   npm install
   ```
2. Start the development server:
   ```bash
   npm run dev
   ```

## Deployment

Any pushes to the `main` branch will automatically trigger a GitHub Action to build and deploy the project to GitHub Pages. Ensure GitHub Pages is configured to use GitHub Actions in the repository settings.
