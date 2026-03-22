# Lake Ozarks Grotto Website

Welcome to the Lake Ozarks Grotto website! This README will help you set up and deploy your website to GitHub Pages.

## 📁 File Structure

Your website consists of the following HTML pages:

- **index.html** - Main homepage with hero section, gallery slider, and overview
- **about.html** - About the grotto, history, mission, and leadership
- **gallery.html** - Photo gallery with filtering and lightbox features
- **goodwin-pit.html** - Information about Goodwin Pit cave
- **events.html** - Current and upcoming events, meetings, and activities
- **speleograph.html** - Newsletter archives and subscription
- **contact.html** - Contact information and meeting details

## 🖼️ Images Folder

All images should be placed in a folder named **images** in your root directory:

```
Lake_ozarks_grotto_website/
├── index.html
├── about.html
├── gallery.html
├── goodwin-pit.html
├── events.html
├── speleograph.html
├── contact.html
├── images/
│   ├── Logo1.png (or .jpg, .webp - your logo)
│   ├── --2.webp
│   ├── --3.webp
│   ├── [... all other cave photos]
│   └── rs=w-984,h-738.webp
└── README.md
```

## 🚀 Deploying to GitHub Pages

1. **Create a GitHub repository** (if you haven't already):
   - Go to https://github.com/databasedinnovations
   - Click "New Repository"
   - Name it: `Lake_ozarks_grotto_website`
   - Make it Public
   - Click "Create repository"

2. **Upload your files**:
   - Upload all HTML files to the root of the repository
   - Create an `images` folder and upload all your photos

3. **Enable GitHub Pages**:
   - Go to repository Settings
   - Scroll to "Pages" section
   - Under "Source", select "Deploy from a branch"
   - Select branch: `main` (or `master`)
   - Select folder: `/ (root)`
   - Click "Save"

4. **Access your website**:
   - Your site will be available at: https://databasedinnovations.github.io/Lake_ozarks_grotto_website/

## 🎨 Customization

### Adding the Logo
Place your logo file (Logo1.png, Logo1.jpg, or Logo1.webp) in the `images/` folder. If you want to display it on the homepage, you can add it by modifying the hero section in index.html.

### Updating Content
- **Events**: Edit `events.html` to update meeting schedules and upcoming activities
- **Newsletter**: Update `speleograph.html` with new issues and archives
- **Gallery**: Add new photos to the `images/` folder and update the image arrays in both `index.html` and `gallery.html`
- **Contact Info**: Update email addresses and meeting locations in `contact.html`

### Color Scheme
The site uses a consistent orange/blue color palette:
- Primary Orange: #ff8c00
- Secondary Orange: #ff6b35
- Dark Blue: #2c3e50
- Light Gray: #7f8c8d

To change colors, search for these hex codes in the HTML files and replace them.

## 📱 Mobile Responsive

All pages are fully responsive and will work on:
- Desktop computers
- Tablets
- Mobile phones

The navigation automatically converts to a mobile menu on smaller screens.

## 🔗 Navigation Structure

All pages are linked through a consistent navigation menu:
- Home → About → Gallery → Goodwin Pit → Current Events → Speleograph → Contact

## ✉️ Contact Forms

The contact form in `contact.html` uses a basic `mailto:` link. For a more robust solution, consider:
- Using a form service like Formspree, Google Forms, or Netlify Forms
- Setting up a backend with PHP or Node.js
- Using a static site generator with form handling

## 📝 Notes

- All HTML files are self-contained with inline CSS and JavaScript
- No external dependencies required (works offline)
- Images are loaded from the `images/` folder
- The gallery supports filtering by category
- Lightbox functionality is built-in for the gallery

## 🆘 Support

For questions or issues:
- Contact: contact@lakeozarksgrotto.com
- GitHub Issues: Create an issue in your repository

## 📜 License

© 2025 Lake Ozarks Grotto. All rights reserved.

---

**Your website is ready to go live!** Simply follow the deployment steps above to publish it on GitHub Pages.
