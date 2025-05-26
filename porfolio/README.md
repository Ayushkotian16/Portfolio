# Ayush R Kotian Portfolio Website

This is the source code for my personal portfolio website showcasing my skills, projects, and contact information.

## Deployment Instructions

### Deploying on GitHub Pages

1. Ensure all your website files (`index.html`, `styles.css`, `script.js`, and any assets) are committed to a GitHub repository under your account: [https://github.com/Ayushkotian16](https://github.com/Ayushkotian16).
2. Navigate to your repository on GitHub.
3. Click on the **Settings** tab.
4. Scroll down to the **Pages** section.
5. Under **Source**, select the branch you want to publish from (usually `main` or `master`) and the root folder (`/`).
6. Click **Save**.
7. Your website will be published at: `https://ayushkotian16.github.io/<repository-name>/`.

### Adding Local Projects to GitHub

1. For each local project you want to showcase, create a new repository on GitHub.
2. In your local project directory, initialize git if not already done:
   ```
   git init
   git add .
   git commit -m "Initial commit"
   ```
3. Add the remote repository URL:
   ```
   git remote add origin https://github.com/Ayushkotian16/<repository-name>.git
   ```
4. Push your project to GitHub:
   ```
   git push -u origin main
   ```
5. Repeat for all projects you want to display on your portfolio.

### Linking Projects on Your Portfolio Website

- The portfolio website dynamically fetches and displays your public GitHub repositories using the GitHub API.
- Ensure your projects are public repositories on GitHub.
- The "GitHub Projects" section on your website will automatically update to show your latest repositories.

## Previewing Locally

Open `index.html` in your browser to preview the website locally.

## Customization

- Modify `index.html` to update personal details or add new sections.
- Edit `styles.css` to change the website's appearance.
- Update `script.js` to add interactivity or customize GitHub API integration.

---

If you need assistance with customization or deployment, feel free to reach out.
