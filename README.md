# Hi 👋, I'm Dashotz

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
</div>
<h3 style="color: #007bff; margin: 16px 0;">Software and Hardware Specialist</h3>
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
