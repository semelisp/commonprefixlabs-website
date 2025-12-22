# Consulting Company Website

A modern, responsive static website for a consulting company with three main pages: Home, Company Details, and Owners Details.

## Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations
- **Three Main Pages**:
  - Home page with hero section, services overview, and company preview
  - Company Details page with comprehensive company information
  - Owners Details page showcasing company owners and their information
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Fast Loading**: Lightweight static site with no dependencies

## File Structure

```
labswebsite/
├── index.html              # Home page
├── company-details.html    # Company details page
├── owners-details.html     # Owners details page
├── styles.css              # Main stylesheet
├── script.js               # JavaScript for navigation
└── README.md               # This file
```

## Customization

### Updating Company Information

1. **Company Details** (`company-details.html`):
   - Edit the company name, registration number, tax ID, etc.
   - Update contact information (address, phone, email)
   - Modify business activities list
   - Update company description

2. **Owners Details** (`owners-details.html`):
   - Update owner names, titles, and ownership percentages
   - Modify roles and experience
   - Update email addresses
   - Edit owner biographies

3. **Home Page** (`index.html`):
   - Update hero section text
   - Modify service descriptions
   - Update company preview section

### Styling

Edit `styles.css` to customize:
- Colors: Modify CSS variables in `:root` selector
- Fonts: Change the `font-family` in the `body` selector
- Spacing: Adjust padding and margins
- Layout: Modify grid and flexbox properties

## Deployment

### Option 1: GitHub Pages

1. Create a new repository on GitHub
2. Upload all files to the repository
3. Go to Settings > Pages
4. Select the main branch as the source
5. Your site will be available at `https://yourusername.github.io/repository-name/`

### Option 2: Netlify

1. Sign up/login to [Netlify](https://www.netlify.com/)
2. Drag and drop the project folder to Netlify's deploy area
3. Your site will be live immediately with a generated URL
4. Optionally, connect to a Git repository for continuous deployment

### Option 3: Vercel

1. Sign up/login to [Vercel](https://vercel.com/)
2. Import your project (GitHub, GitLab, or Bitbucket)
3. Vercel will automatically detect it as a static site
4. Deploy with one click

### Option 4: Traditional Web Hosting

1. Upload all files to your web hosting provider via FTP/SFTP
2. Ensure `index.html` is in the root directory
3. Your site should be accessible immediately

### Option 5: AWS S3 + CloudFront

1. Create an S3 bucket
2. Enable static website hosting
3. Upload all files to the bucket
4. Optionally, set up CloudFront for CDN distribution

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Technologies Used

- HTML5
- CSS3 (with CSS Grid and Flexbox)
- Vanilla JavaScript (no frameworks or dependencies)

## License

This project is open source and available for use and modification.

## Support

For questions or issues, please refer to the project documentation or contact the development team.

