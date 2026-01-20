# Portfolio Website

A clean, responsive personal portfolio website built with pure HTML and CSS, showcasing education, skills, projects, and professional experience.

## Overview

This is a modular portfolio website with separate HTML pages for different sections, each with its own dedicated stylesheet. The component-based structure makes it easy to maintain and update individual sections independently.

## Features

- **Pure HTML & CSS** - No frameworks, no JavaScript, no dependencies
- **Modular Architecture** - Separate files for each section (navbar, education, skills, projects, experience, footer)
- **Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- **Fast Loading** - Minimal code means quick page loads
- **Easy to Maintain** - Component-based structure for simple updates
- **GitHub Pages Ready** - Already deployed and configured for GitHub hosting

## Project Structure

```
portfolio/
│
├── index.html              # Main landing page
├── style.css               # Main stylesheet
│
├── navbar.html             # Navigation bar component
├── navbar.css              # Navigation styling
│
├── edu.html                # Education section
├── edu_style.css           # Education styling
│
├── skills.html             # Skills section
├── style_skills.css        # Skills styling
│
├── projects.html           # Projects showcase
├── project_style.css       # Projects styling
│
├── experience.html         # Work experience
├── experience_style.css    # Experience styling
│
├── footer.html             # Footer component
├── footer_style.css        # Footer styling
│
└── image2.png              # Assets/images
```

## Getting Started

### Local Development

1. **Clone** the repository:
   ```bash
   git clone https://github.com/yourusername/portfolio.git
   ```

2. **Navigate** to the project folder:
   ```bash
   cd portfolio
   ```

3. **Open** `index.html` in your browser to view the site locally

### Viewing Online

The site is deployed on GitHub Pages at:
```
https://yourusername.github.io/portfolio
```

## Customization

### Updating Content

Each section can be edited independently:
- **Navigation**: Edit `navbar.html` and `navbar.css`
- **Education**: Update `edu.html` and `edu_style.css`
- **Skills**: Modify `skills.html` and `style_skills.css`
- **Projects**: Change `projects.html` and `project_style.css`
- **Experience**: Edit `experience.html` and `experience_style.css`
- **Footer**: Update `footer.html` and `footer_style.css`

### Adding New Sections

1. Create new HTML file (e.g., `contact.html`)
2. Create corresponding CSS file (e.g., `contact_style.css`)
3. Link the CSS in your HTML file
4. Update navigation links in `navbar.html`

## Deployment

This portfolio is deployed on **GitHub Pages**. To update:

1. Make your changes locally
2. Commit and push to the main branch:
   ```bash
   git add .
   git commit -m "Update portfolio content"
   git push origin main
   ```
3. Changes will be live in a few minutes

### First-time GitHub Pages Setup

If not already configured:
1. Go to repository Settings
2. Navigate to Pages section
3. Select main branch as source
4. Save and wait for deployment

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Styling and responsive design
- **GitHub Pages** - Free static site hosting
