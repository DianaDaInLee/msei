# MSEI: Multi-Site Experiment Initiative

This repository contains the website for the Multi-Site Experiment Initiative (MSEI), a large-scale, fully funded survey platform for cross-national experimentation.

## About MSEI

MSEI enables researchers to field coordinated multi-site experiments across 10 countries at no cost. We fund 15 successful proposals in the first two years (7 in year one, 8 in year two) to generate comparable evidence across diverse contexts and advance understanding of external validity.

## Website Structure

- **index.html** - Home page with MSEI overview
- **about-us.html** - Team information (PIs, RAs, Selected Teams)
- **msei.html** - Detailed description of the initiative
- **call-for-proposal.html** - Proposal requirements and submission
- **for-applicants.html** - FAQ for applicants
- **for-reviewers.html** - FAQ for reviewers
- **css/style.css** - Website styling

## Setting Up GitHub Pages

To publish this website using GitHub Pages:

1. Go to your repository settings on GitHub
2. Navigate to "Pages" in the left sidebar
3. Under "Source", select the branch you want to use (usually `main`)
4. Select the root folder `/` as the source
5. Click "Save"

Your website will be available at: `https://[your-username].github.io/msei/`

## Local Development

To view the website locally:

1. Clone this repository
2. Open `index.html` in your web browser
3. Or use a local server:
   ```bash
   python -m http.server 8000
   ```
   Then visit `http://localhost:8000`

## Customization

### Adding Team Members

Edit `about-us.html` and add team member information in the appropriate sections:
- Principal Investigators
- Research Assistants
- Selected Teams

### Updating Content

- Edit the HTML files directly to update content
- Modify `css/style.css` to change styling and colors
- Update proposal submission link in `call-for-proposal.html`

### Changing Colors

The main color scheme uses:
- Primary: `#667eea` (purple-blue)
- Secondary: `#2c3e50` (dark blue-gray)
- Accent: `#764ba2` (purple)

Update these in `css/style.css` to match your branding.

## License

© 2026 Multi-Site Experiment Initiative. All rights reserved.
