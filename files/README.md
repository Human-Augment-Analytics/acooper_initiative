# Real-World Collaboration Initiative - Sub-Website

This is a dedicated sub-website for the **Real-World Collaboration Initiative**, housed within HAAG (Georgia Tech's online research initiative). This site documents the framework for building sustainable partnerships between academic research and real-world organizations.

## Overview

The initiative addresses a gap many academic researchers face: How do we move from good research ideas to meaningful partnerships with real-world organizations? Using the Charleston Trains case study as our proof of concept, we're building a documented, replicable procedure.

## Site Structure

### Pages

- **index.html** - Initiative homepage with overview and quick links
- **case-study.html** - Charleston Trains case study (proof of concept)
- **procedure.html** - The documented framework for real-world collaborations
- **faq.html** - Frequently asked questions about partnerships
- **contact.html** - Contact information for different audiences

### Supporting Files

- **styles.css** - Shared stylesheet (updated with sub-site colors and breadcrumb styling)
- **script.js** - Navigation and TOC functionality

## Key Features

✓ **Sub-site positioning** - Subtle branding showing this is part of HAAG, with breadcrumb navigation
✓ **Procedure-focused** - Emphasizes the framework, not general HAAG services
✓ **Case study evidence** - Charleston Trains demonstrates the procedure in action
✓ **Multiple audiences** - Content for faculty, researchers, external organizations, and other universities
✓ **Responsive design** - Works on mobile, tablet, and desktop
✓ **No external dependencies** - HTML, CSS, vanilla JS only

## What Changed from Original

### Navigation
- Removed: Partnerships, Opportunities pages
- Added: Procedure page (core of initiative)
- Updated: All nav menus to reflect initiative focus

### Branding
- **Header** - Smaller, more subtle for sub-site positioning
- **Colors** - Secondary Georgia Tech blue (--primary: #004a73, --accent: #0080d0)
- **Breadcrumbs** - Added navigation showing "← HAAG / Initiative / Page Name"
- **Footer** - Now emphasizes "Part of HAAG"

### Content
- **Homepage** - Reframed as initiative overview, not general HAAG overview
- **Case Study** - Repositioned as proof-of-concept for the procedure
- **FAQ** - Initiative-specific questions about partnerships
- **Contact** - Tailored to people interested in the initiative

### Removed Files
- `opportunities.html` - Not relevant for sub-site
- `partnerships.html` - Replaced by `procedure.html`
- `avi_cooper_initiative.md` - Internal planning document
- Original `README.md`

## Audience & Use

### For HAAG Faculty
Learn the procedure for helping research projects engage external partners and pursue collaborative funding.

### For HAAG Researchers
Understand when and how to initiate conversations about real-world collaboration on your work.

### For External Organizations
Explore how HAAG can help address research-backed challenges through structured partnerships.

### For Other Universities
Adapt this framework for your own research groups and community partnerships.

## Customization

To adapt this for your needs:

1. **Email addresses** - Replace `rwc-initiative@gatech.edu` with actual contact email
2. **Names/Titles** - Update `[Name, Title]` in footer
3. **HAAG URL** - Update breadcrumb link from `https://haag.gatech.edu/` to actual HAAG homepage
4. **Colors** - If needed, adjust CSS variables in styles.css
5. **Content** - Refine descriptions of the procedure phases and research areas

## How to Use

1. Download all files to a folder
2. Open `index.html` in a web browser
3. All navigation links will work locally or on a web server

## Browser Support

Works in all modern browsers (Chrome, Firefox, Safari, Edge)

## Mobile Responsive

Fully responsive with optimized layouts for:
- Desktop (1200px+)
- Tablet (768px - 1199px)
- Mobile (< 768px)

## Typography

- **Headings**: Merriweather (serif) - professional, academic
- **Body**: Source Sans Pro (sans-serif) - clean, readable
- Fonts loaded from Google Fonts CDN

## Color Scheme

- **Primary**: #004a73 (Secondary Georgia Tech blue)
- **Accent**: #0080d0 (Bright blue)
- **Text**: #1a1a1a (Dark gray)
- **Background**: #fafafa (Off-white)

## Files to Deploy

```
├── index.html
├── case-study.html
├── procedure.html
├── faq.html
├── contact.html
├── styles.css
└── script.js
```

All files are self-contained with no external dependencies beyond Google Fonts (which loads from CDN).

---

**Last Updated**: April 2026
**Initiative Lead**: [Name, Title]
