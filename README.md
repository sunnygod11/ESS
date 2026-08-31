# ESS - Energy Storage System

A comprehensive project for testing and monitoring energy storage systems with detailed routine test reports.

## Files

- **routine_test_report (14).html** - MEA Routine Test Report for Inverter systems with PDF generation capabilities

## Viewing the Reports

### Option 1: View on Vercel (Recommended)
The project is configured to deploy on Vercel for easy online access:

1. Connect your GitHub repository to Vercel
2. Vercel will automatically deploy on every push
3. Access your HTML report at: `https://your-vercel-app.vercel.app/routine_test_report%20(14).html`

### Option 2: Local Viewing
Download the HTML file and open it directly in your web browser.

### Option 3: GitHub Pages
Enable GitHub Pages in repository settings to access at: `https://sunnygod11.github.io/ESS/routine_test_report%20(14).html`

### Option 4: Online HTML Preview
Use an HTML preview service by visiting:
```
https://htmlpreview.github.io/?https://github.com/sunnygod11/ESS/blob/main/routine_test_report%20(14).html
```

## Features

- PDF generation using jsPDF library
- HTML to canvas conversion with html2canvas
- Spreadsheet support with xlsx.js
- Professional test report formatting
- Custom fonts (Sarabun embedding)

## Deployment on Vercel

The repository includes a `vercel.json` configuration file that enables automatic deployment:

1. **Sign up on Vercel** (free tier available)
2. **Import this repository** from GitHub
3. **Deploy** - Vercel will automatically build and deploy on every push
4. **Access** - Your HTML files will be publicly accessible via your Vercel domain

### Vercel Configuration

```json
{
  "buildCommand": "echo 'Build complete'",
  "outputDirectory": ".",
  "framework": "other"
}
```

This configuration tells Vercel to:
- Simply echo a message during build (no complex build needed for static HTML)
- Use the current directory as output
- Treat it as a static site project

## Quick Start

1. Clone the repository
2. Open `routine_test_report (14).html` in a web browser
3. Or deploy to Vercel for online access

## Technologies Used

- **jsPDF** - PDF document generation from JavaScript
- **html2canvas** - Convert HTML to canvas/images
- **xlsx.js** - Spreadsheet processing
- **Custom CSS** - Professional styling with embedded fonts

---

For more information or issues, please check the GitHub repository.
