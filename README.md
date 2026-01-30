# Portfolio Website

A modern, responsive personal portfolio website showcasing my projects, skills, and experience as an AI/ML Engineering student.

## 🚀 Features

- **Responsive Design**: Fully responsive layout that works seamlessly on desktop, tablet, and mobile devices
- **Smooth Animations**: Interactive typing effect for role display and smooth scrolling navigation
- **Modern UI/UX**: Dark theme with gradient accents and glassmorphism effects
- **Project Showcase**: Video demonstrations of featured projects
- **Mobile Navigation**: Hamburger menu for mobile devices with smooth slide-in animation
- **Active Section Highlighting**: Navigation links automatically highlight based on scroll position
- **Fixed Social Links**: Always-visible social media links at the bottom of the viewport

## 🛠️ Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Modern styling with CSS variables, flexbox, and grid
- **JavaScript (Vanilla)**: Interactive functionality and animations
- **Font Awesome**: Icons for social media and UI elements
- **Google Fonts**: Poppins font family

## 📁 Project Structure

```
portfillo/
│
├── index.html          # Main HTML file
├── style.css           # All styling and responsive design
├── script.js           # JavaScript functionality
├── vinay.jpg          # Profile picture
├── vinay.pdf          # Resume file
│
└── Project Videos/     # Video demonstrations
    ├── Attendance.mp4
    ├── calculator.mp4
    ├── Car video.mp4
    ├── earth vinay.mp4
    ├── vedio2.mp4
    └── weather app.mp4
```

## 🎯 Sections

1. **Hero Section**: Introduction with animated typing effect and call-to-action buttons
2. **About Section**: Personal journey, current status, and language proficiency
3. **Skills Section**: Technical skills organized by categories:
   - Programming Languages (C, C++, Python, Java, HTML, CSS, JavaScript, DSA)
   - Frameworks & Libraries (TensorFlow, PyTorch, OpenCV, Hugging Face, Langchain, Flask, Streamlit, Pandas, Scikit-Learn, NumPy, Seaborn)
   - AI & Machine Learning (ML, Deep Learning, NLP, LLM, BERT, GPT, LLaMA, RAG Agents)
   - Soft Skills (Team Management, Communication, Problem Solving, Creative Thinking, Innovation)
4. **Projects Section**: Six featured projects with video demos and GitHub links
5. **Contact Section**: Social media links and email contact

## 🎨 Design Features

- **Color Scheme**: Dark navy background with purple-pink gradient accents
- **Typography**: Poppins font family with varying weights
- **Custom Scrollbar**: Styled scrollbar matching the theme
- **Gradient Effects**: Multiple gradient applications for visual appeal
- **Hover Effects**: Interactive hover states on cards and links
- **Glassmorphism**: Frosted glass effect on header

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px
- **Small Mobile**: Below 480px

## 🚀 Getting Started

### Prerequisites

No build tools or dependencies required! Just a modern web browser.

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Vinay-KumarMishra/Portfolio.git
```

2. Navigate to the project directory:
```bash
cd Portfolio
```

3. Open `index.html` in your web browser:
   - Simply double-click the file, or
   - Use a local server (recommended for development):
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js (if you have http-server installed)
     npx http-server
     ```

4. Access the website at `http://localhost:8000` (or the port specified)

## 📝 Customization

### Updating Personal Information

1. **Profile Picture**: Replace `vinay.jpg` with your own image
2. **Resume**: Replace `vinay.pdf` with your resume file
3. **Personal Details**: Edit the content in `index.html`:
   - Hero section (name, roles, description)
   - About section (journey, status)
   - Contact links (social media URLs, email)

### Modifying Colors

Edit CSS variables in `style.css`:
```css
:root {
    --page-bg: #0C1E32;
    --dark-navy: #0A192F;
    --light-navy: #112240;
    --green-accent: #64FFDA;
    --gradient-start: #8A2BE2;
    --gradient-end: #FF1493;
    /* ... more variables */
}
```

### Adding Projects

1. Add a new project card in the projects section of `index.html`
2. Include a video file in the project directory
3. Update the video source path
4. Add project description and GitHub link

### Modifying Typing Animation

Edit the roles array in `script.js`:
```javascript
const roles = [
    "Your role 1",
    "Your role 2",
    // Add more roles
];
```

## 🌐 Live Demo

Visit the live portfolio: [Add your deployed URL here]

## 📧 Contact

- **Email**: vinaymishra3012@gmail.com
- **GitHub**: [@Vinay-KumarMishra](https://github.com/Vinay-KumarMishra)
- **LinkedIn**: [Vinay Kumar Mishra](https://www.linkedin.com/in/vinay-kumar-mishra-a70688330)
- **Instagram**: [@vinay_mishra6074](https://www.instagram.com/vinay_mishra6074)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Font Awesome for icons
- Google Fonts for typography
- All the open-source communities that make web development possible

## 📈 Future Enhancements

- [ ] Add dark/light theme toggle
- [ ] Implement blog section
- [ ] Add project filtering by technology
- [ ] Integrate contact form with backend
- [ ] Add analytics tracking
- [ ] Implement lazy loading for videos
- [ ] Add more interactive animations

---

**Built with ❤️ by Vinay Kumar Mishra**

