# Fluffy Jump

A classic jumping game built with p5.js. Guide a character through obstacles with simple one-tap controls.
bezier, p5js, creative-coding, generative-art, interactive-art, javascript

![Gameplay Screenshot]
<img width="602" height="343" alt="image" src="https://github.com/user-attachments/assets/92aab27e-329e-4108-9cb9-6497b4875d31" />


## ▶️ Live Demo
Play directly in your browser:  
[https://editor.p5js.org/Joy_yiling_zhong/sketches/GwOavhZmd](https://editor.p5js.org/Joy_yiling_zhong/sketches/GwOavhZmd)

## 🎮 Controls
- **SPACE key** to jump
- Avoid fireballs to keep playing
- Score increases over time

## ⚙️ Technical Features
- **p5.js** for rendering
- **Bezier-inspired jump physics** (quadratic curve)
- Mobile-responsive design
- Zero dependencies

```javascript
// Example jump calculation (simplified)
function jump() {
  // Uses quadratic bezier for smooth arc
  let y = bezierPoint(startY, peakY, endY, t);
}

## 📥 Local Installation
# Just open index.html or link in any browser!
