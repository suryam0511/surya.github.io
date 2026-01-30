# Surya Prakash - Cloud DevOps Engineer Portfolio

A modern, responsive portfolio website showcasing cloud infrastructure expertise, DevOps automation skills, and professional projects.

## 🚀 Features

- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Dark/Light Theme**: Toggle between themes with persistent preference storage
- **Modern UI**: Clean, minimalistic design with smooth animations
- **ATS-Friendly**: Embedded keywords for better searchability
- **Performance Optimized**: Fast loading with efficient CSS and JavaScript
- **Accessibility**: WCAG compliant with proper focus management
- **Auto-Deploy**: GitHub Actions workflow for automatic deployment

## 🌐 Live Demo

Visit the live portfolio: [https://your-username.github.io](https://your-username.github.io)

## 📁 Project Structure

```
portfolio/
├── .github/
│   └── workflows/
│       └── deploy.yml     # GitHub Actions deployment workflow
├── index.html             # Main HTML file
├── styles.css             # CSS styles with theme support
├── script.js              # JavaScript functionality
├── profile.jpg            # Profile image
├── README.md              # Project documentation
└── DEPLOYMENT.md          # Deployment guide
```

## 🚀 Quick Deployment

### Deploy to GitHub Pages:
1. **Create Repository**: `your-username.github.io` on GitHub
2. **Upload Files**: Push all files to the repository
3. **Enable Pages**: Go to Settings → Pages → Source: "GitHub Actions"
4. **Auto-Deploy**: Every push automatically deploys your site!

📖 **Detailed Instructions**: See [DEPLOYMENT.md](DEPLOYMENT.md) for complete setup guide.

## 🛠 Technologies Used

- **HTML5**: Semantic markup with proper meta tags
- **CSS3**: Modern CSS with CSS Grid, Flexbox, and CSS Variables
- **JavaScript**: Vanilla JS for theme toggle and smooth scrolling
- **Font Awesome**: Icons for visual enhancement
- **GitHub Actions**: Automated deployment workflow
- **GitHub Pages**: Free hosting platform

## 🎨 Customization

### Adding New Projects

1. Open `index.html`
2. Find the `projects-grid` section
3. Add a new `project-card` div with the following structure:

```html
<div class="project-card">
    <div class="project-header">
        <h3>Project Title</h3>
        <div class="project-tags">
            <span class="tag">Technology</span>
            <span class="tag">Tool</span>
        </div>
    </div>
    <p class="project-description">
        Project description with ATS-friendly keywords...
    </p>
    <div class="project-highlights">
        <ul>
            <li>Achievement 1</li>
            <li>Achievement 2</li>
            <li>Achievement 3</li>
        </ul>
    </div>
</div>
```

### Updating Skills

1. Navigate to the `skills-grid` section in `index.html`
2. Add new skill categories or update existing ones
3. Use the `skill-tag` class for individual skills

### Modifying Theme Colors

1. Open `styles.css`
2. Update CSS variables in the `:root` selector for light theme
3. Update CSS variables in the `[data-theme="dark"]` selector for dark theme

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: 480px - 767px
- **Small Mobile**: Below 480px

## 🔧 Local Development

1. **Clone Repository**:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. **Open Locally**: Open `index.html` in a web browser

3. **Make Changes**: Edit HTML, CSS, or JS files

4. **Deploy**: Push changes to GitHub for automatic deployment

## 📊 SEO & ATS Optimization

The portfolio includes:
- **Meta Tags**: Proper title, description, and keywords
- **Semantic HTML**: Structured markup for better crawling
- **ATS Keywords**: Naturally embedded throughout content
- **Performance**: Optimized loading for better search rankings

## 🎯 Key Sections

1. **Hero Section**: Professional introduction with call-to-action
2. **Skills**: Categorized technical competencies
3. **Projects**: Detailed project showcases with achievements
4. **Contact**: Multiple contact methods with social links

## 🔄 Automatic Deployment

The repository includes a GitHub Actions workflow that:
- ✅ Automatically deploys on every push to main branch
- ✅ Builds and optimizes the site
- ✅ Updates live site within 2-3 minutes
- ✅ Provides deployment status and logs

## 🔄 Future Enhancements

- [ ] Add project detail modals
- [ ] Implement contact form
- [ ] Add blog section
- [ ] Include testimonials
- [ ] Add resume download
- [ ] Integrate analytics

## 📞 Contact Information

- **Email**: suryaprakashm0511@gmail.com
- **LinkedIn**: [linkedin.com/in/suryaprakash0511](https://www.linkedin.com/in/suryaprakash0511/)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

**Built with ❤️ for Cloud DevOps professionals**