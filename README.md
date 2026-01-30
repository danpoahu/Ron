# Barclay Bible Commentaries Web App

A modern, responsive web application for browsing William Barclay's Daily Study Bible commentaries.

## Features

- **Search**: Full-text search across all 1,980 commentary entries
- **Filter by Book**: Drop-down to filter by specific book/section
- **Sort Options**: Sort by reference or book title
- **Pagination**: Easy navigation through results (20 per page)
- **Responsive Design**: Works perfectly on mobile, tablet, and desktop
- **Read More/Less**: Collapsible commentary text for better readability

## Files Included

- `index.html` - The complete web application (standalone, no dependencies)
- `commentaries.csv` - All 1,980 commentary entries in CSV format

## Quick Start

### Option 1: Simple Local Testing
1. Put both `index.html` and `commentaries.csv` in the same folder
2. Open `index.html` in your web browser
3. That's it! The app will work locally

### Option 2: Deploy to GitHub Pages (FREE)
1. Create a new GitHub repository
2. Upload both files to the repository
3. Go to Settings → Pages
4. Select "Deploy from branch" → main branch → root folder
5. Your site will be live at: `https://[username].github.io/[repo-name]`

### Option 3: Deploy to Firebase Hosting
1. Install Firebase CLI: `npm install -g firebase-tools`
2. Create a new folder and put both files in it
3. Run: `firebase init hosting`
4. Select your project (or create new one)
5. Set public directory to current folder (`.`)
6. Configure as single-page app: No
7. Don't overwrite index.html
8. Run: `firebase deploy --only hosting`

### Option 4: Deploy to Netlify (Drag & Drop)
1. Go to https://app.netlify.com/drop
2. Drag both files onto the page
3. Your site will be instantly deployed!

## CSV Format

The CSV file has the following columns:
- **book**: The section/book title
- **reference**: Bible verse reference (e.g., "Matt 1:1-17")
- **title**: Commentary section title (if any)
- **commentary**: The full commentary text

## Data Source

This commentary data is from William Barclay's Daily Study Bible series, containing 1,980 entries covering various books of the Bible.

## Browser Compatibility

Works in all modern browsers:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Customization

The app uses CSS variables for easy theming. Edit these in the `:root` section of `index.html`:

```css
:root {
    --primary-color: #2c3e50;
    --secondary-color: #3498db;
    --accent-color: #e74c3c;
    --bg-color: #ecf0f1;
}
```

## No Dependencies

This is a completely standalone application with:
- No external JavaScript libraries
- No build process required
- No server-side code needed
- Just HTML, CSS, and vanilla JavaScript

## Performance

- Fast loading: All data loaded once on page load
- Instant search and filtering (client-side)
- Optimized for 1,980+ entries
- Smooth animations and transitions

## Future Enhancements (Optional)

If you want to add more features:
- Add to Firebase for online sync across devices
- Add bookmarking functionality
- Add notes/annotations
- Add verse cross-references
- Export search results

## License

Commentary content © William Barclay's Daily Study Bible
Web application created for personal/church use

## Support

For issues or questions about deployment, feel free to reach out!
