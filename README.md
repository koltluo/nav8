# My Hugo Site
🚀 A static website built with  and deployed automatically to **GitHub Pages** using **GitHub Actions**.
## 🔗 Live Demo
- **Website URL:** [https://koltluo.github.io/nav8/](https://koltluo.github.io/nav8/)
*(Replace with your actual GitHub Pages URL)*
## 🛠️ Features
- **Hugo Static Site Generator** – Fast, flexible, and easy to use.
- **GitHub Pages Hosting** – Free and reliable hosting.
- **GitHub Actions CI/CD** – Automated build & deployment on every `git push`.
- **Responsive Design** – Works on mobile, tablet, and desktop.
- **Custom Domain Support** – Optional (see setup below).
## 🚀 Quick Start
### Prerequisites
- [Hugo](https://gohugo.io/installation/) (Extended version recommended)
- [Git](https://git-scm.com/)
- A [GitHub](https://github.com/) account
### Local Development
1. **Clone the repository:**
   ```bash
   git clone https://github.com/koltluo/nav8.git
   cd my-hugo-site
   ```
2. **Run Hugo locally:**
   ```bash
   hugo server -D  # Starts a local dev server (http://localhost:1313)
   ```
   *(Use `-D` to include draft posts.)*
3. **Edit content:**
   - Modify Markdown files in `content/`
   - Customize themes in `themes/`
   - Update site config in `config.toml`/`config.yaml`
4. **Preview changes:**
   The site auto-reloads at `http://localhost:1313`.
### Deployment (Automatic via GitHub Actions)
- Every push to `main` branch triggers a GitHub Actions workflow:
  - Builds Hugo site → Generates static files in `public/`
  - Deploys to `gh-pages` branch → Live on GitHub Pages
*(No manual steps needed!)*
## ⚙️ Configuration
### GitHub Pages Setup
1. Go to **Settings → Pages**
2. Set **Source** to `gh-pages` branch
3. Wait for GitHub Actions to complete (~1-2 min)
### Custom Domain (Optional)
1. Add a `CNAME` file in `static/` with your domain (e.g., `example.com`)
2. Configure DNS (CNAME record pointing to `your-username.github.io`)
3. Enable HTTPS in GitHub Pages settings
## 📂 Project Structure
```
my-hugo-site/
├── archetypes/       # Content templates
├── assets/           # SCSS, JS bundles
├── content/          # Markdown content (pages, posts)
├── layouts/          # HTML templates
├── static/           # Images, fonts, CNAME
├── themes/           # Hugo themes
├── config.toml       # Site configuration
└── .github/workflows/deploy.yml  # GitHub Actions CI/CD
```
## 📜 License
This project is open-source under the [MIT License](LICENSE).
---
🛠 **Need help?**
- [Hugo Documentation](https://gohugo.io/documentation/)
- [GitHub Pages Docs](https://docs.github.com/en/pages)
- [GitHub Actions Docs](https://docs.github.com/en/actions)
```
---
### ✨ Customization Tips:
1. **Replace placeholders** (`your-username`, `my-hugo-site`, etc.) with your actual details.
2. **Add badges** (e.g., GitHub Actions status, license, Hugo version):
   ```markdown
   ![Hugo Version](https://img.shields.io/badge/Hugo-v0.120.4-blue)
   ```
3. **Add screenshots** in a `/static/images/` folder and embed them:
   ```markdown
   ![Site Preview](/images/screenshot.png)
   ```
4. **Include theme credits** if using a third-party Hugo theme.
Let me know if you'd like to add/remove any sections!