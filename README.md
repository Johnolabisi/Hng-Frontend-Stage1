# HNG-Frontend-Stage1
# HNG Internship - Stage 1 Task

A responsive portfolio website with Contact Us and About Me pages, built with semantic HTML, accessibility features, and form validation as part of the HNG internship Stage 1 task.

## 🚀 Live Demo

[Add your live URL here after deployment]

## 📁 Project Structure

```
Hng-Frontend-Stage1/
├── index.html          # Main Profile Page (Stage 0)
├── about.html          # About Me Page (Stage 1)
├── contact.html        # Contact Us Page (Stage 1)
├── style.css           # Main Stylesheet
├── Home.css           # Profile Page Styles (Legacy)
├── script.js           # Form Validation & Functionality
├── imgjohn.jpg         # Profile Image
└── README.md           # This file
```

## 🎯 Task Requirements Completed

### ✅ Contact Us Page
- **Form with validation** for all required fields
- **Required fields with data-testid attributes:**
  - `test-contact-name` - Full name input
  - `test-contact-email` - Email input
  - `test-contact-subject` - Subject input
  - `test-contact-message` - Message textarea
  - `test-contact-submit` - Submit button
  - `test-contact-error-<field>` - Error messages
  - `test-contact-success` - Success message
- **Validation rules:**
  - All fields required
  - Email format validation (name@example.com)
  - Message minimum 10 characters
- **Accessibility features:**
  - Proper `<label>` associations with `for` attributes
  - `aria-describedby` for error messages
  - `aria-live` regions for dynamic content
  - Keyboard navigation support

### ✅ About Me Page
- **Reflective sections with data-testid attributes:**
  - `test-about-page` - Main container
  - `test-about-bio` - Bio section
  - `test-about-goals` - Goals in program section
  - `test-about-confidence` - Areas of low confidence
  - `test-about-future-note` - Note to future self
  - `test-about-extra` - Extra thoughts section
- **Semantic HTML structure:**
  - `<main>` wrapper
  - `<section>` for each content area
  - Proper heading hierarchy (`<h1>`, `<h2>`)
  - Accessible navigation

### ✅ General Requirements
- **Semantic HTML** throughout all pages
- **Fully responsive** design (mobile, tablet, desktop)
- **Accessibility compliance:**
  - Alt text for images
  - ARIA attributes
  - Keyboard navigation
  - Focus indicators
- **Clean, modular code** structure

## 🛠 Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with CSS variables
- **JavaScript** - Form validation and interactivity
- **CSS Grid & Flexbox** - Responsive layouts
- **CSS Custom Properties** - Consistent theming

## 🎨 Design Features

- **Dark theme** with purple accents
- **Responsive navigation** that adapts to mobile devices
- **Card-based layouts** with subtle shadows and borders
- **Smooth transitions** and hover effects
- **Consistent spacing** and typography
- **Accessible color contrast** ratios

## 📱 Responsive Breakpoints

- **Mobile**: < 768px
- **Tablet**: 768px - 1024px  
- **Desktop**: > 1024px

## 🚀 Setup & Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Johnolabisi/Hng-Frontend-Stage1.git
   cd Hng-Frontend-Stage1
   ```

2. **Serve the files** using a local server
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   
   # Using PHP
   php -S localhost:8000
   ```

3. **Open in browser**
   Navigate to `http://localhost:8000`

## 🧪 Testing

### Manual Testing Checklist
- [ ] Form validation shows appropriate error messages
- [ ] Success message appears on valid submission
- [ ] All pages are fully responsive
- [ ] Keyboard navigation works correctly
- [ ] Screen reader announces form errors and success
- [ ] Images have proper alt text
- [ ] Color contrast meets accessibility standards

### Automated Testing
The project includes `data-testid` attributes for all required elements to facilitate automated testing.

## 🌐 Deployment

### Netlify
1. Push code to GitHub
2. Connect repository to Netlify
3. Deploy with default settings

### GitHub Pages
1. Go to repository Settings → Pages
2. Select "Deploy from branch" → main branch
3. Site available at: `https://johnolabisi.github.io/HNG-Frontend-Stage1`

### Vercel
1. Import project from GitHub
2. Deploy with zero configuration

## 📝 Notes

- This project builds upon Stage 0 task requirements
- All form validation is client-side using vanilla JavaScript
- The design follows modern web standards and accessibility guidelines
- Code is organized for readability and maintainability

## 🔧 Browser Support

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## 📞 Contact

**John Olabisi**
- GitHub: [@Johnolabisi](https://github.com/Johnolabisi)
- LinkedIn: [John Olabisi](https://www.linkedin.com/in/john-olabisi-24543638b/)

## 📄 License

This project is created as part of the HNG internship program. All rights reserved.

---

**HNG Internship** • [Learn more about HNG](https://hng.tech) • [HNG Hire](https://hng.tech/hire)
