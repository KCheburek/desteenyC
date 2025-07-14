# Desteeny Organization Website

A modern, responsive website for the Desteeny organization, which connects people through skill sharing and community collaboration. We bring together individuals who want to teach and learn from each other, while also volunteering with local organizations to make a positive impact.

## 🌟 Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations
- **Three Main Pages**:
  - **Home**: Introduction, mission, and community impact
  - **About**: Organization story, values, programs, and team
  - **Join Our Community**: Ways to get involved and Google Form application
- **Interactive Elements**: Mobile navigation, form handling, and smooth scrolling
- **Accessibility**: Keyboard navigation and screen reader friendly

## 📁 File Structure

```
cursorwebsite/
├── index.html              # Home page
├── about.html              # About page
├── involvement.html        # Join Our Community page
├── styles.css              # Main stylesheet
├── script.js               # JavaScript functionality
├── google-form-template.md # Google Form setup instructions
└── README.md               # This file
```

## 🚀 Hosting on GitHub Pages

### Method 1: Using GitHub Repository (Recommended)

1. **Create a GitHub Repository**:
   - Go to [GitHub](https://github.com) and sign in
   - Click the "+" icon and select "New repository"
   - Name your repository (e.g., `desteeny-website`)
   - Make it public
   - Don't initialize with README (we already have one)

2. **Upload Your Files**:
   ```bash
   # Clone the repository
   git clone https://github.com/YOUR_USERNAME/desteeny-website.git
   
   # Copy all website files to the repository folder
   # (index.html, about.html, involvement.html, styles.css, script.js, README.md)
   
   # Add files to git
   git add .
   
   # Commit changes
   git commit -m "Initial website upload"
   
   # Push to GitHub
   git push origin main
   ```

3. **Enable GitHub Pages**:
   - Go to your repository on GitHub
   - Click "Settings" tab
   - Scroll down to "Pages" section
   - Under "Source", select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click "Save"

4. **Your Website URL**:
   - Your site will be available at: `https://YOUR_USERNAME.github.io/desteeny-website`

### Method 2: Using GitHub Desktop

1. Download and install [GitHub Desktop](https://desktop.github.com/)
2. Sign in with your GitHub account
3. Click "Clone a repository from the Internet"
4. Select your repository
5. Choose a local path and click "Clone"
6. Copy all website files to the cloned folder
7. In GitHub Desktop, you'll see the changes
8. Add a commit message and click "Commit to main"
9. Click "Push origin" to upload to GitHub
10. Follow steps 3-4 from Method 1 to enable GitHub Pages

## 🎨 Customization

### Colors
The website uses a blue color scheme. To change colors, edit the CSS variables in `styles.css`:

```css
/* Primary blue color */
--primary-color: #2563eb;

/* Secondary colors */
--secondary-color: #1d4ed8;
--accent-color: #667eea;
```

### Content
- **Organization Name**: Update "Desteeny" throughout the HTML files
- **Contact Information**: Update email and phone in the footer
- **Statistics**: Modify the impact numbers in `index.html`
- **Team Members**: Update team information in `about.html`
- **Programs**: Customize program descriptions in `about.html`
- **Google Form**: Set up the application form using the template in `google-form-template.md`

### Images
To add real images:
1. Create an `images/` folder
2. Add your images (recommended formats: JPG, PNG, WebP)
3. Update the HTML to reference your images instead of Font Awesome icons

## 📱 Mobile Optimization

The website is fully responsive and includes:
- Mobile-first design approach
- Touch-friendly navigation
- Optimized typography for small screens
- Fast loading times

## 🔧 Technical Details

- **HTML5**: Semantic markup for accessibility
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript**: Vanilla JS for interactivity
- **Fonts**: Inter font family from Google Fonts
- **Icons**: Font Awesome 6.0
- **No Dependencies**: Pure HTML, CSS, and JavaScript

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📞 Support

If you need help with:
- **GitHub Pages setup**: Check [GitHub Pages documentation](https://pages.github.com/)
- **Customization**: Modify the HTML and CSS files as needed
- **Adding features**: The code is well-commented and modular

## 📄 License

This website template is created for the Desteeny organization. Feel free to modify and use for your own organization.

---

**Desteeny** - Connecting people through skill sharing and community collaboration. 
## 📄 License

This website template is created for the Desteeny organization. Feel free to modify and use for your own organization.

---

**Desteeny** - Empowering immigrants through education, communication, and mentorship. 
