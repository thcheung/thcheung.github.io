# CHEUNG Tsun Hin - Personal Website

[![GitHub Pages](https://img.shields.io/badge/Deployed%20on-GitHub%20Pages-blue)](https://thcheung.github.io)
[![Jekyll](https://img.shields.io/badge/Built%20with-Jekyll-red)](https://jekyllrb.com/)

Personal portfolio website showcasing research work, publications, and projects in Machine Learning and AI.

## 🌐 Live Site

Visit the live site at: [https://thcheung.github.io](https://thcheung.github.io)

## 🎨 Design

- **Design Inspiration**: Discord's modern dark mode aesthetic
- **Color Scheme**: Dark navy/blue theme with Discord's signature blurple (#5865F2)
- **Typography**: GG Sans (Discord's custom font) with fallbacks
- **Features**:
  - Fixed navigation bar with smooth scrolling
  - Responsive mobile design with hamburger menu
  - Dark mode optimized for readability
  - Interactive hover effects and animations
  - Glassmorphism effects

## 📑 Sections

- **Research Interests**: Machine Learning, NLP, Large Language Models
- **Development Skills**: PyTorch, HuggingFace, LangChain, React.js, and more
- **Projects**: Current and past research projects (2019-2025)
- **Publications**: 9 peer-reviewed papers with direct links to publishers

## 🛠️ Technologies

- **Static Site Generator**: Jekyll
- **Hosting**: GitHub Pages
- **Styling**: Custom CSS with CSS Variables
- **Font**: GG Sans, Inter
- **Icons**: Unicode symbols

## 📚 Publications

The site features publications from:
- IEEE Xplore
- ScienceDirect (Neurocomputing, Knowledge-Based Systems)
- ACM Digital Library
- MDPI (Sensors)
- SPIE Digital Library

## 🚀 Local Development

### Prerequisites

- Ruby (2.5.0 or higher)
- Bundler
- Jekyll

### Setup

1. Clone the repository:
```bash
git clone https://github.com/thcheung/thcheung.github.io.git
cd thcheung.github.io
```

2. Install dependencies:
```bash
bundle install
```

3. Run the development server:
```bash
bundle exec jekyll serve --safe
```

Or use the provided script:
```bash
./run.sh
```

4. Open your browser and navigate to `http://localhost:4000`

## 📝 Structure

```
.
├── _config.yml          # Jekyll configuration
├── _layouts/            # Page layouts
│   ├── home.html       # Main homepage layout
│   ├── default.html
│   ├── page.html
│   ├── post.html
│   └── project.html
├── _includes/          # Reusable components
├── _posts/             # Blog posts (if any)
├── _sass/              # Sass stylesheets
├── assets/             # Static assets (images, CSS, JS)
├── index.markdown      # Homepage content
└── *.markdown          # Individual project pages

```

## 🔄 Updating Content

### Add a New Publication

Edit `_layouts/home.html` and add a new list item in the Publications section:

```html
<li>
  <strong>Your Name</strong> and Co-authors, "<a href="LINK_TO_PAPER" target="_blank">Paper Title</a>," Conference/Journal, Year.
</li>
```

### Update Research Interests or Skills

Edit the corresponding sections in `_layouts/home.html` and add/remove keyword badges:

```html
<span class="keyword-badge">New Skill</span>
```

### Add a New Project

Add a new list item in the Projects section with title and duration:

```html
<li>
  <h3>
    <strong>Project Title</strong>
    <span class="p-duration">(Year - Year)</span>
  </h3>
</li>
```

## 📱 Responsive Design

The site is fully responsive with breakpoints at:
- **Desktop**: > 768px
- **Tablet**: 481px - 768px
- **Mobile**: ≤ 480px

Mobile features include:
- Collapsible hamburger navigation
- Optimized typography scaling
- Touch-friendly interactive elements

## 🎨 Color Variables

The site uses CSS custom properties for easy theme customization:

```css
--discord-blurple: #5865F2;
--background-color: #313338;
--background-secondary: #2b2d31;
--text-color: #f2f3f5;
```

## 📄 License

This project is open source and available under the MIT License.

## 📧 Contact

- **Email**: tsun-hin.cheung@connect.polyu.hk
- **LinkedIn**: [https://www.linkedin.com/in/tsunhincheung](https://www.linkedin.com/in/tsunhincheung)
- **GitHub**: [https://github.com/thcheung](https://github.com/thcheung)
- **Google Scholar**: [Profile Link](https://scholar.google.com/citations?user=v5UKVvAAAAAJ&hl=en)

---

© 2025 CHEUNG Tsun Hin. All Rights Reserved.
