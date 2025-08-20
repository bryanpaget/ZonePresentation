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

## 📁 Repository Structure

```
├── .github/workflows/
│   └── deploy.yml          # GitHub Action for deployment
├── slides.md               # Main presentation file
├── marp-config.yml         # Marp configuration
├── canada.png              # Canada flag image
├── kubeflow-logo.png       # Kubeflow logo
├── kubernetes-logo.png     # Kubernetes logo
├── sas-logo.png            # SAS logo
├── data-science-bg.png     # Data science background
├── dashboard-bg.png        # Dashboard background
├── best-practices.png      # Best practices image
├── tools-bg.png            # Tools background
├── limitations-bg.png      # Limitations background
└── future-bg.png           # Future background
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
![bg right:30%](your-image.png)
```

## 🔄 Deployment Process

This repository uses GitHub Actions to automatically convert and deploy the presentation:

1. **Checkout**: The repository is checked out
2. **Conversion**: Marp CLI converts the Markdown to HTML and PDF
3. **Upload**: The generated files are uploaded as artifacts
4. **Deploy**: The files are deployed to GitHub Pages

The deployment is triggered automatically when changes are pushed to the main branch.

## 📊 Presentation Sections

1. **Title Slide**: Introduction to The Zone
2. **What is The Zone?**: Overview of the platform
3. **Key Benefits**: Cost efficiency, flexibility, and open source advantages
4. **What is Kubeflow?**: Explanation of the underlying technology
5. **Access & Status**: How to access and current usage statistics
6. **Best Practices**: Tips for optimizing workflow
7. **Tools & Environments**: Available development environments
8. **SAS Support**: Transitioning from SAS to open source
9. **Limitations**: Current challenges and solutions
10. **Future**: Planned enhancements and features

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📧 Contact

For questions or suggestions, please open an issue in this repository.
