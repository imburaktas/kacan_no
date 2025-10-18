# 💕 Coffee? - The Elusive "NO" Button

[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen)](https://imburaktas.github.io/kacan_no/)
[![HTML](https://img.shields.io/badge/HTML-5-orange)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS](https://img.shields.io/badge/CSS-3-blue)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

> 👉👈 A fun interactive page where the "NO" button runs away from you!

An entertaining web project featuring a playful question with a twist - you can't say no! The "NO" button escapes whenever you try to click it, while the "YES" button grows bigger and more tempting.

---

## 🌟 Demo

**👉 [Try it Live!](https://imburaktas.github.io/kacan_no/)**

*Warning: You might get frustrated trying to click "NO"!* 😄

---

## 📸 Preview

<img width="1911" height="832" alt="image" src="https://github.com/user-attachments/assets/98f9a125-dad3-4118-ab71-75210101073d" />


*Try to catch the "NO" button... if you can!*

---

## ✨ Features

- 🏃 **Escaping NO Button** - Moves away when you hover/approach
- 📈 **Growing YES Button** - Gets bigger with each NO attempt
- 😍 **Celebration Screen** - Special message when you click YES
- 🎮 **Interactive Animation** - Smooth CSS animations
- 📱 **Fully Responsive** - Works on all devices
- 🎨 **Cute Design** - Fun and playful interface

---

## 🎯 How It Works

1. **User sees the question:** "Coffee? 👉👈" 
2. **Two buttons appear:** YES and NO
3. **Hover over NO:** The button runs away!
4. **Each escape:** YES button grows larger
5. **Click YES:** Celebration screen appears! 😍
6. **Try to click NO:** Good luck with that! 😏

---

## 🛠️ Technologies Used

- **HTML5** - Structure
- **CSS3** - Styling & Animations
- **JavaScript** - Interactive logic
- **GitHub Pages** - Hosting

---

## 🚀 Installation

### To run locally:

1. **Clone the repository:**
```bash
git clone https://github.com/imburaktas/kacan_no.git
cd kacan_no
```

2. **Open in browser:**
```bash
# Simply double-click the index.html file

# Or use a local server:
python -m http.server 8000
# Then open: http://localhost:8000
```

---

## 📁 Project Structure

```
kacan_no/
├── index.html          # Main page
├── css/
│   └── style.css       # Styles and animations
├── js/
│   └── script.js       # Interactive logic
├── img/                # Images (if any)
└── README.md           # Documentation
```

---

## 🎨 Code Highlights

### JavaScript Logic
```javascript
// NO button runs away on hover
noButton.addEventListener('mouseover', () => {
    const randomX = Math.random() * (window.innerWidth - 100);
    const randomY = Math.random() * (window.innerHeight - 50);
    noButton.style.position = 'absolute';
    noButton.style.left = randomX + 'px';
    noButton.style.top = randomY + 'px';
    
    // YES button grows bigger
    yesButton.style.transform = 'scale(1.2)';
});
```

### CSS Animations
```css
button {
    transition: all 0.3s ease;
}

button:hover {
    transform: scale(1.1);
}
```

---

## 💡 Inspiration

This project is inspired by the classic "impossible to say no" interactive pages that have become popular on social media. Perfect for:

- 💝 Asking someone out
- 🎉 Fun pranks
- 🎓 Learning JavaScript interactions
- 😄 Making people laugh

---

## 🎮 Try These Variations

You can customize the project for different occasions:

- **Valentine's Day** - "Be my Valentine?"
- **Prom Invitation** - "Go to prom with me?"
- **Birthday Party** - "Come to my party?"

---

## 🤝 Contributing

Contributions are welcome! Feel free to:

1. Fork the project
2. Create your feature branch
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. Commit your changes
   ```bash
   git commit -m 'Add some AmazingFeature'
   ```
4. Push to the branch
   ```bash
   git push origin feature/AmazingFeature
   ```
5. Open a Pull Request

### Ideas for Contributions:
- 🌍 Multi-language support
- 🎵 Add sound effects
- 🎨 More themes/styles
- 📊 Track escape attempts
- 🏆 Achievement system

---

## 📝 License

This project is open source and available for personal use.

---

## 👤 Author

**Buraktaş**

- GitHub:https://github.com/imburaktas
- LinkedIn: www.linkedin.com/in/burak-aktaş-63359326b

---

## 🙏 Acknowledgments

- Inspired by viral "you can't say no" memes
- Thanks to the JavaScript community
- Special shoutout to everyone who tried to click "NO" 😂

---


---

## 🎭 Fun Facts

- 🏃 Average NO button escapes before giving up: **7-10**
- 😅 Frustration level: **Maximum**
- 💯 Success rate of clicking NO: **0%**
- 😍 Happiness when clicking YES: **Over 9000!**

---

<div align="center">

### 👉👈 Will you try to click NO?

Made with ❤️ and 😏 by [Buraktaş](https://github.com/imburaktas)

**[⭐ Star this repo](https://github.com/imburaktas/kacan_no)** if you enjoyed the chase!

</div>
