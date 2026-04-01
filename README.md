# Aniket Kumar - Portfolio Website

Personal portfolio showcasing Senior Software Engineer expertise in OneRoster API, C#, .NET, and EdTech systems. Modern, responsive design built with pure HTML/CSS/JS—no frameworks. 

## 🚀 Features
- **Responsive Design**: Perfect on desktop, tablet, mobile (edu-cards stack cleanly).
- **Dark/Light Theme**: Toggle via nav button.
- **Smooth Animations**: Hero typing, CGPA rings, floating particles, hover effects.
- **Equal-Width Cards**: Fixed education cards (680px max, balanced padding).
- **Performance Optimized**: CSS-only animations, lightweight (no JS bloat).
- **Sections**: Hero, About, Skills, Experience, Projects, Achievements, Education, Con
Personal portfolio showcasing Senior Software Engineer expertise in OneRoster API, C#, .NET, and EdTech systems. Modern, responsive design built with pure HTML/CSS/JS—no frameworks.
## 🚀 Features
- **Responsive Design**: Perfect on desktop, tablet, mobile (edu-cards stack cleanly).
- **Dark/Light Theme**: Toggle via nav button.
- **Smooth Animations**: Hero typing, CGPA rings, floating particles, hover effects.
- **Equal-Width Cards**: Fixed education cards (680px max, balanced padding).
- **Performance Optimized**: CSS-only animations, lightweight (no JS bloat).
- **Sections**: Hero, About, Skills, Experience, Projects, Achievements, Education, Contact.
## 📱 Mobile Fixes Applied
- **Edu-Cards**: `flex-direction:column`, 1.8rem L/R padding, CGPA/logo centered.
- **Equal Sizing**: `max-width:680px` + `margin:auto` for uniform horizontal width.
- **Awards Section**: Proper stacking, hover preserved.
- **No Overflow**: `min-width:0` + text wrapping.
## 🛠️ File Structure
```
portfolio/
├── index.html (paste.txt)  # Complete site
└── README.md              # This file
```
## 🎨 Customization
| Element | CSS Variable | Example |
|---------|--------------|---------|
| Primary Accent | `--accent` | `#00d4aa` (teal) |
| Secondary | `--accent2` | `#0099ff` (blue) |
| Background | `--bg` | `#090c10` (dark) |
| Text | `--text` | `#e8edf3` |

**Edit**: Search for `:root[data-theme="dark"]` to change colors.
## 📱 Testing Responsiveness
```
Chrome DevTools → Toggle Device Toolbar
- Desktop: 1440px ✓ Equal cards
- Tablet: 768px ✓ Stacked properly  
- Mobile: 375px ✓ Full-width, no scroll
```
## 🔧 Quick Edits
- **Add Education**: Duplicate `.edu-card`, update `.edu-degree`, `.edu-cgpa-value`.
- **Skills**: Edit `.skill-fill {width: XX%}` percentages.
- **Theme Toggle**: Flip `data-theme="light"` in `<html>`.
## 🚀 Deployment
```bash
# Static hosting (free)
- GitHub Pages: Upload to repo
- Netlify: Drag-drop folder
- Vercel: `vercel --prod`
```

**Live Demo**: Render `index.html` in any browser—fully self-contained.

***

**Built by Aniket Kumar** | India | March 2026  
