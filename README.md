
# My Portfolio Website
Hey there! 👋 This is my personal portfolio website that I built to showcase my work, skills, an
journey as a developer. I'm Mkonzo Shirlean, and I'm currently studying Computer Science at Kisii University while working as a mobile developer, graphic designer, and cybersecurity analyst.

## What I Built

I created this portfolio using pure HTML, CSS, and vanilla JavaScript - no frameworks needed! I wanted something clean, modern, and fully responsive that represents who I am and what I can do. The design features a beautiful gradient background with glassmorphism effects that I'm really proud of.

## Features I Included

### Main Sections
- **Hero Section** - I added a cool typewriter effect that cycles through my roles (Mobile Developer, Graphic Designer, Cybersecurity Analyst, etc.)
- **About Me** - My story, timeline, and some stats about my work
- **Projects** - A filterable grid where I showcase my best work
- **Skills** - Animated progress bars that show my technical skills
- **Contact** - A working contact form (though you'll need to set up email integration if you want it to actually send emails)

### Cool Interactive Stuff
- ✅ **Dark Mode** - I love dark mode, so I made sure to include a toggle that remembers your preference
- ✅ **Smooth Scrolling** - Everything scrolls smoothly between sections
- ✅ **Mobile Menu** - Hamburger menu for mobile devices (because most people browse on phones these days)
- ✅ **Project Filtering** - You can filter my projects by category (Web, Mobile, Design, AI)
- ✅ **Scroll Animations** - Sections fade in as you scroll - I used Intersection Observer for this
- ✅ **Form Validation** - The contact form validates inputs in real-time
- ✅ **Progress Bar** - Shows how far you've scrolled
- ✅ **Back to Top Button** - Appears after you scroll down a bit

### Design Choices
- 🎨 **Gradient Background** - I went with a blue/purple/pink gradient that I think looks really nice
- 🎨 **Glassmorphism** - All the cards have that frosted glass effect - it's trendy and I love how it looks
- 🎨 **Smooth Animations** - Everything has smooth transitions and animations
- 🎨 **Responsive** - Works great on mobile, tablet, and desktop

## How to Use It

It's super simple - just open `Index.html` in your browser! No build process, no dependencies, nothing fancy. Just pure HTML, CSS, and JavaScript.

If you want to use this as a template for your own portfolio:
1. Download or clone the files
2. Open `Index.html` in your code editor
3. Replace my information with yours
4. Update the projects, skills, and timeline sections
5. Customize the colors if you want

## File Structure

```
.
├── Index.html    # Everything is in one file (easier to manage)
└── README.md     # This file
```

I kept it simple - everything in one HTML file makes it easy to edit and deploy.

## Customizing for Your Own Use

If you want to use this for your portfolio, here's where to update things:

**Personal Info:**
- Hero section (around line 793) - Change the name, title, and description
- About section (around line 838) - Update the bio, tags, stats, and timeline
- Contact section (around line 970) - Your email, phone, location, social links

**Projects:**
- Find the `projects` array in the JavaScript (around line 1000)
- Add your own projects with images, descriptions, and tech stacks

**Skills:**
- Update the `skillsData` array (around line 1080)
- Adjust the proficiency levels to match your actual skills

**Colors:**
- The color scheme is in CSS variables at the top (around line 35)
- Change the `--primary` and `--secondary` colors to match your brand

**Background:**
- The gradient is in the `body` styles (around line 66)
- Feel free to experiment with different gradient colors!

## Technologies I Used

- **HTML5** - Semantic, accessible markup
- **CSS3** - Custom properties, Grid, Flexbox, and lots of animations
- **Vanilla JavaScript** - No frameworks, just pure JS
- **Font Awesome** - For icons (loaded via CDN)
- **Google Fonts** - Poppins for headings, Inter for body text

I intentionally avoided frameworks because I wanted to keep it simple and lightweight. Plus, it's a good way to show I understand the fundamentals.

## About the Contact Form

The contact form has validation built in, but it doesn't actually send emails yet. If you want to make it functional, you can integrate it with:
- [EmailJS](https://www.emailjs.com/) - Super easy to set up
- [Formspree](https://formspree.io/) - Another good option
- Your own backend API - If you have one set up

I'll probably add EmailJS integration later, but for now it's set up to show success/error messages.

## Performance & Accessibility

I tried to make this as performant and accessible as possible:
- Images are lazy-loaded
- Scroll events are debounced
- Used Intersection Observer for efficient scroll animations
- All animations use `transform` and `opacity` for better performance
- Semantic HTML with proper ARIA labels
- Keyboard navigation support
- Good contrast ratios for readability

## Browser Support

Works great on:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

I tested it on all major browsers and it should work fine. If you find any issues, let me know!

## About Me

I'm Mkonzo Shirlean, a:
- 📱 Mobile Developer (proficient in Flutter/Dart)
- 🎨 Graphic Designer
- 🔒 Cybersecurity Analyst
- 💻 Full Stack Developer

Currently a student at Kisii University (started in 2024) and a Power Learn Project graduant. I'm passionate about building secure, beautiful applications that solve real problems.

**Contact:**
- Email: shirlean262@gmail.com
- Phone: +254116992392
- Location: Nairobi, Kenya

## Credits & Thanks

- Font Awesome for the icons
- Google Fonts for the beautiful typography
- Unsplash for placeholder images
- All the developers whose portfolios inspired me

## License

Feel free to use this as a template for your own portfolio! Just make sure to replace my content with yours. 😊

---

**Built with HTML, CSS, and JavaScript - no frameworks, just pure code.**

Thanks for checking out my portfolio! If you have any questions or feedback, feel free to reach out.
