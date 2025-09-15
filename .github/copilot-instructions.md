# GitHub Copilot Instructions

## Repository Overview

This repository hosts a privacy policy for the "Unpolished" mobile application as a static HTML website deployed via GitHub Pages. The privacy policy is designed to comply with various data privacy regulations including GDPR, CCPA, and COPPA.

## Project Structure

- `privacy_policy.html` - Main privacy policy document (self-contained HTML with embedded CSS)
- `.github/workflows/` - GitHub Actions workflows for automated deployment
- `README.md` - Project documentation

## Key Context

### Application Details
- **App Name**: "Unpolished" 
- **Platform**: Mobile application
- **Monetization**: Google AdMob banner advertisements
- **Data Collection**: Minimal - only AdMob advertising data and local last-read page storage
- **Target Audience**: General audience (not directed at children under 13)
- **Compliance**: GDPR/CCPA compliant with UMP consent management

### Website Purpose
- Provides a canonical URL for the app's privacy policy
- Serves as legal compliance documentation
- Must remain accessible and readable across devices
- Content should be clear and user-friendly

## Coding Guidelines

### HTML Structure
- Keep the privacy policy as a single, self-contained HTML file
- Include all CSS inline within `<style>` tags in the `<head>`
- Maintain responsive design principles
- Use semantic HTML elements for accessibility
- Include proper meta tags for viewport and charset

### Styling Approach
- Use system fonts for maximum compatibility
- Maintain clean, readable typography with good contrast
- Keep styling minimal and professional
- Ensure mobile-friendly responsive design
- Use colors that are accessible (WCAG compliant)

### Content Updates
When updating privacy policy content:
- Always update the effective date in the `<span id="effective-date">` element
- Maintain consistent section structure and hierarchy
- Keep language clear and non-technical where possible
- Preserve all required legal disclosures
- Ensure contact information remains current

### Legal Considerations
- Privacy policy must remain legally accurate
- Changes should be reviewed for compliance implications
- Maintain links to external policies (Google Privacy Policy, AdMob policies)
- Keep app-specific identifiers and contact information current

## Common Tasks

### Updating Effective Date
```html
<span id="effective-date">YYYY-MM-DD</span>
```

### Adding New Data Collection Practices
- Add new sections under "Information We Collect"
- Update the Summary section bullet points
- Consider impact on "How We Use Information" section
- Update retention and sharing sections as needed

### Styling Changes
- Modify the embedded CSS in the `<head>` section
- Test changes across different screen sizes
- Maintain accessibility standards
- Keep consistent with the professional appearance

## Deployment

The site uses GitHub Pages with automated deployment via GitHub Actions. Changes to `privacy_policy.html` are automatically deployed when pushed to the main branch.

## Testing

- Validate HTML structure and syntax
- Check responsive design across different viewport sizes
- Verify all external links are functional
- Ensure accessibility standards are met
- Confirm the effective date reflects actual changes