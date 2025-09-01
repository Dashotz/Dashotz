<h1 align="center">Hi 👋, I'm Dashotz</h1>

<div align="center">
  <div style="display: flex; gap: 8px; justify-content: center; flex-wrap: wrap; margin: 16px 0;">
    <span style="background-color: #6c757d; color: white; padding: 6px 12px; border-radius: 6px; font-size: 14px; font-weight: 500;">DEVELOPER</span>
    <span style="background-color: #20c997; color: white; padding: 6px 12px; border-radius: 6px; font-size: 14px; font-weight: 500;">FULL STACK</span>
    <span style="background-color: #6c757d; color: white; padding: 6px 12px; border-radius: 6px; font-size: 14px; font-weight: 500;">TECHNICAL</span>
    <span id="flipping-text" style="background-color: #fd7e14; color: white; padding: 6px 12px; border-radius: 6px; font-size: 14px; font-weight: 500;">SOFTWARE</span>
    <span style="background-color: #6c757d; color: white; padding: 6px 12px; border-radius: 6px; font-size: 14px; font-weight: 500;">Connect with me</span>
    <span style="background-color: #28a745; color: white; padding: 6px 12px; border-radius: 6px; font-size: 14px; font-weight: 500;">dashotz14@gmail.com</span>
  </div>
  
  <h3 style="color: #007bff; margin: 16px 0;">Full Stack Developer</h3>
  <h3 style="color: #007bff; margin: 16px 0;">Software and Hardware Specialist</h3>
</div>
---

<h1 align="center">🧐 About Me</h1>


```javascript
const dashotz = {
  languages: ["Python", "JavaScript", "PHP", "HTML", "CSS"],
  frameworks: ["React.js", "Node.js", "Laravel"],
  interests: ["Web Development", "Automation", "Educational Tools"],
  currentFocus: "Building user-friendly web applications",
  funFact: "I love turning complex problems into elegant solutions!"
};
```

---


---

<div align="center">
  <h3>🚀 Let's Connect!</h3>
  <a href="mailto:dashotz14@gmail.com" target="_blank">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://linkedin.com/in/dashotz" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://twitter.com/dashotz" target="_blank">
    <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter" />
  </a>
</div>

<script>
  const flippingText = document.getElementById('flipping-text');
  const texts = ['SOFTWARE', 'HARDWARE'];
  let currentIndex = 0;
  
  function flipText() {
    currentIndex = (currentIndex + 1) % texts.length;
    flippingText.textContent = texts[currentIndex];
  }
  
  setInterval(flipText, 3000);
</script>
