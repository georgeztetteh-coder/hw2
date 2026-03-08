=====================================
PARADIGM — Multi-Page Portfolio Website
README.txt
=====================================

Name: [Your Name Here]

What I Built:
A 4-page portfolio website called "Paradigm" — a fictional creative studio.
Pages: Home (index.html), About (about.html), Gallery (gallery.html), Contact (contact.html)
Stack: HTML5 + CSS3 only. No frameworks, no build tools.

File Structure:
  paradigm-site/
  ├── index.html       Home page with hero slider, about preview, services, gallery preview, CTA, contact form
  ├── about.html       About page with alternating two-column sections, team cards, skill bars
  ├── gallery.html     Gallery page with 12-image grid and filter buttons
  ├── contact.html     Contact page with map placeholder, full form (6 fields), and FAQ section
  ├── style.css        Single shared stylesheet for all pages
  ├── images/          Folder for all images (see image list below)
  └── README.txt       This file

Images Used (place your images here with these filenames):
  images/about.jpg         — main about image (home page)
  images/about-1.jpg       — studio photo (about page, section 1)
  images/about-2.jpg       — process photo (about page, section 2)
  images/team-1.jpg        — team member 1
  images/team-2.jpg        — team member 2
  images/team-3.jpg        — team member 3
  images/gallery-1.jpg     — gallery image 1
  images/gallery-2.jpg     — gallery image 2
  images/gallery-3.jpg     — gallery image 3
  images/gallery-4.jpg     — gallery image 4
  images/gallery-5.jpg     — gallery image 5
  images/gallery-6.jpg     — gallery image 6
  images/gallery-7.jpg     — gallery image 7
  images/gallery-8.jpg     — gallery image 8
  images/gallery-9.jpg     — gallery image 9
  images/gallery-10.jpg    — gallery image 10
  images/gallery-11.jpg    — gallery image 11
  images/gallery-12.jpg    — gallery image 12

What Parts I Asked ChatGPT For:
- Initial folder structure and section outline planning
- Hero slider CSS animation logic
- CSS custom properties design system (color variables, spacing scale)
- Contact form HTML structure

What I Changed Manually After ChatGPT Output:
- Rewrote CSS from scratch using a custom design system (CSS variables)
- Replaced generic color scheme with a dark navy + blue palette
- Added responsive breakpoints for mobile, tablet, and desktop
- Added accessibility attributes (aria-label, aria-current, aria-expanded, alt text)
- Added gallery filter functionality
- Added form submission success feedback
- Added scroll-triggered navbar background change
- Fixed all relative file paths
- Ensured consistent header/footer across all 4 pages
- Added CSS-only hero slider (no JS libraries used)
- Added breadcrumb navigation on inner pages

Notes:
- The hero slider uses pure CSS transitions triggered by a small inline script
  (no external JS library). The assignment allows CSS-based sliders.
- The gallery filter is a lightweight vanilla JS implementation with no libraries.
- All images use relative paths (images/filename.jpg).
- Replace placeholder images with your actual provided images from the images/ folder.
=====================================
