# The Zone Presentation

This repository contains the presentation slides for "The Zone: A Modern Data Science Platform" built with Marp and automatically deployed to GitHub Pages.

## 📋 Overview

The presentation showcases The Zone, a Kubeflow-based data science platform that supports Python, R, and SAS within a unified environment. It highlights the platform's benefits, features, and future direction for business managers.

## 🚀 Quick Start

### Viewing the Presentation

The presentation is automatically deployed to GitHub Pages and available at: [https://bryanpaget.github.io/ZonePresentation/](https://bryanpaget.github.io/ZonePresentation/)

### Local Development

To view or edit the slides locally:

1. Install [Marp CLI](https://github.com/marp-team/marp-cli)
2. Clone this repository
3. Run the following command to preview the slides:

```bash
npx @marp-team/marp-cli slides.md --preview
```

## 🛠️ Customization

### Editing Slides

The presentation is written in Markdown using Marp syntax. To edit:

1. Open `slides.md` in your favorite editor
2. Modify the content as needed
3. Commit and push changes to trigger automatic deployment

### Styling

The presentation uses a custom style defined in `marp-config.yml`. Key features include:

- Navy blue header and footer with Statistics Canada branding
- Red maple leaf in the footer
- Consistent 16:9 aspect ratio
- Custom background colors for different sections

### Adding Images

To add new images:

1. Place image files in the root directory
2. Reference them in the slides using Marp's image syntax:

```markdown
![bg right:33%](your-image.png)
```

## 🔄 Deployment Process

This repository uses GitHub Actions to automatically convert and deploy the presentation:

1. **Checkout**: The repository is checked out
2. **Conversion**: Marp CLI converts the Markdown to HTML and PDF
3. **Upload**: The generated files are uploaded as artifacts
4. **Deploy**: The files are deployed to GitHub Pages

The deployment is triggered automatically when changes are pushed to the main branch.

