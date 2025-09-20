# Personal Portfolio - Jekyll Website

A personal portfolio website built with Jekyll, showcasing skills, experience, and projects. This site provides an in-depth look at John Micheal Acera's background and work.

## 🚀 Features

- **Personal Portfolio**: Showcase your skills, experience, and projects
- **Blog Posts**: Share insights and guides (like the "Guide to Beginners in Software Development")
- **About Me**: Personal introduction and background
- **Contact**: Easy way for visitors to get in touch
- **Responsive Design**: Built with Jekyll's minima theme for mobile-friendly experience
- **Social Links**: Connect with GitHub and Twitter profiles

## 📋 Prerequisites

Before you begin, ensure you have the following installed:
- Ruby 3.3.0 or later
- Bundler gem
- Git

## 🛠️ Installation

1. **Clone the repository**
   ```bash
   git clone <your-repository-url>
   cd jekyll-app
   ```

2. **Install dependencies**
   ```bash
   bundle install
   ```

3. **Serve the site locally**
   ```bash
   bundle exec jekyll serve
   ```

4. **View your site**
   Open your browser and navigate to `http://localhost:4000`

## 📁 Project Structure

```
jekyll-app/
├── _config.yml          # Site configuration
├── _includes/           # Reusable components
├── _posts/              # Blog posts
│   ├── 2023-03-18-hello-jm.md
│   ├── 2023-03-18-hello-world.md
│   ├── 2023-03-18-welcome-to-jekyll.markdown
│   └── 2024-03-16-guide-to-beginners-in-software-development.md
├── 404.html             # Custom 404 page
├── aboutme.md           # About page
├── contact.md           # Contact page
├── index.md             # Homepage
├── portfolio.md         # Portfolio page
├── Gemfile              # Ruby dependencies
├── Gemfile.lock         # Locked dependency versions
└── README.md            # This file
```

## ⚙️ Configuration

The site configuration is managed in `_config.yml`. Key settings include:

- **Site Title**: Personal Portfolio
- **Author**: John Micheal Acera
- **Email**: jmmonacera@gmail.com
- **Theme**: minima
- **Social Links**: GitHub and Twitter profiles

## 📝 Adding Content

### Blog Posts
Create new blog posts in the `_posts/` directory with the naming convention:
```
YYYY-MM-DD-title.md
```

### Pages
Add new pages by creating `.md` files in the root directory and updating the `header_pages` section in `_config.yml`.

## 🎨 Customization

### Theme
This site uses the Jekyll minima theme. To customize:
1. Override theme files by creating files with the same name in your site directory
2. Modify `_config.yml` for theme-specific settings

### Styling
- CSS files can be added to `assets/css/`
- Override theme styles by creating files in `_sass/`

## 🚀 Deployment

### GitHub Pages
1. Push your code to a GitHub repository
2. Enable GitHub Pages in repository settings
3. Select source branch (usually `main` or `gh-pages`)

### Other Platforms
- **Netlify**: Connect your repository and deploy automatically
- **Vercel**: Import your repository and deploy
- **Traditional Hosting**: Build the site with `bundle exec jekyll build` and upload the `_site` folder

## 📚 Resources

- [Jekyll Documentation](https://jekyllrb.com/docs/)
- [Minima Theme](https://github.com/jekyll/minima)
- [Markdown Guide](https://www.markdownguide.org/)

## 🤝 Contributing

This is a personal portfolio site, but if you'd like to suggest improvements or report issues, feel free to open an issue or submit a pull request.

## 📞 Contact

- **Email**: jmmonacera@gmail.com
- **GitHub**: [johnmichealacera](https://github.com/johnmichealacera)
- **Twitter**: [@AceraJm](https://twitter.com/AceraJm)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

Built with ❤️ using Jekyll and the minima theme.
