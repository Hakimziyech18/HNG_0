# Frontend Wizards — Stage 0 Task: Profile Card
This project is my submission for the HNG-13 Frontend Track (Stage 0) task.  
It's a responsive and accessible Profile Card built using semantic HTML, modern CSS and vanilla JavaScript.  
The design follows all the requirements in the task document and includes smooth animations and a gradient design to make the interface visually appealing.

# 🚀 Live Demo
🔗 Live URL: https://hakimiprofilecard.netlify.app/
 
💻 GitHub Repo: https://github.com/Hakimziyech18/HNG_0

#🧠 Project Overview
The Profile Card displays key user details, including:
- Full Name
- Short Biography
- Current Time (in milliseconds)
- Avatar Image
- Social Links (GitHub, Twitter, LinkedIn)
- Hobbies List
- Dislikes List

Every visible element includes a `data-testid` attribute to make automated testing easy and reliable.

# 🧩 Features Implemented
| Feature | Description |
|---------|-------------|
| 🏗 **Semantic HTML Structure** | Used `<article>`, `<header>`, `<section>`, `<figure>`, `<nav>`, and other semantic elements for accessibility. |
| ⏰ Dynamic Time | Displayed current time in milliseconds using `Date.now()` via JavaScript, updating every second. |
| 🎨 Responsive Design | Implemented with Flexbox and CSS media queries (`max-width: 640px` and `min-width: 768px`). |
| 💫 Smooth Animations | Added hover effects and transitions on social links for enhanced user experience. |
| 🎨 Modern Gradient Design | Beautiful gradient backgrounds for body and header sections. |
| ♿ Accessibility | Included `alt` text for images, semantic tags, `aria-labels`, and ensured all links are keyboard-focusable. |
| 🌍 Deployment Ready | Can be easily deployed on Netlify, Vercel, or GitHub Pages. |

# 🛠 Technologies Used
- HTML5
- CSS3 (Flexbox, Gradients, Transitions)
- Vanilla JavaScript (ES6)
- Netlify (Deployment)

# 📂 Folder Structure
```
profile-card/
│
├── index.html
├── Abdulhakeem Sule .jpg
├── github.png
├── twitter.png
├── linkedin.png
└── README.md
```

# ⚙️ How to Run Locally
1. **Clone the repository:**
   ```bash
   git clone https://github.com/Hakimziyech18/profile-card.git
   ```

2. **Navigate into the folder:**
   ```bash
   cd profile-card
   ```

3. **Open `index.html` in your browser.**

That's it! 🎉

# ✅ Test IDs Checklist
| Element | data-testid |
|---------|-------------|
| Profile Card | `test-profile-card` |
| Name | `test-user-name` |
| Bio | `test-user-bio` |
| Current Time | `test-user-time` |
| Avatar | `test-user-avatar` |
| Social Links | `test-user-social-links` |
| GitHub Link | `test-user-social-github` |
| Twitter Link | `test-user-social-twitter` |
| LinkedIn Link | `test-user-social-linkedin` |
| Hobbies | `test-user-hobbies` |
| Dislikes | `test-user-dislikes` |

# 🧾 Notes
- All animations were implemented with pure CSS transitions.
- Time updates dynamically every second using JavaScript.
- Layout adjusts seamlessly for mobile, tablet, and desktop screens.
- Social links open in new tabs with `rel="noopener noreferrer"` for security.
- All images include proper `alt` attributes for screen readers.

# 👤 Author
Name: Abdulhakeem Sule  
Track: HNG-13 Frontend Track  
Stage: 0  
Email: Suleadoyiza@gmail.com
GitHub: [@Hakimziyech18](https://github.com/Hakimziyech18)  
Twitter: [@hakiimii18](https://x.com/hakiimii18)  
LinkedIn: [Adoyiza Sule](https://www.linkedin.com/in/adoyiza-sule-5a4b21374)
