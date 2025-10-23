
# 🧮 Counter Program

A simple and interactive **counter application** built using **HTML**, **CSS**, and **JavaScript**.  
This project demonstrates DOM manipulation and basic event handling, making it an excellent beginner-level web development example.

---

## 🚀 Features
- Increase, decrease, and reset the counter dynamically.  
- Real-time update of the counter label using JavaScript.  
- Clean and responsive UI design with hover effects.  
- Lightweight and runs on any modern browser.

---

## 🧰 Technologies Used
- **HTML5** — for page structure  
- **CSS3** — for styling and layout  
- **JavaScript (Vanilla)** — for logic and interactivity  

---

## 📁 Project Structure
```
├── counter program.html
├── counter program style.css
└── counter program script.js
```

---

## 🧩 How It Works
1. The counter starts at **0**.
2. Clicking **Increase** increments the count.
3. Clicking **Decrease** decrements the count.
4. Clicking **Reset** brings the count back to **0**.
5. The current count value updates live on the screen via DOM manipulation.

---

## 💡 Code Overview

### JavaScript Logic (`counter program script.js`)
Handles button events and updates the count label:
```js
increaseButton.onclick = function() {
    count++;
    countLabel.textContent = count;
};
```

### CSS Styling (`counter program style.css`)
Applies central alignment and hover effects:
```css
.buttons:hover {
    background-color: gray;
}
```

### HTML Structure (`counter program.html`)
Defines the UI layout:
```html
<label id="countlabel">0</label>
<div id="buttoncontainer">
  <button id="decreasebutton">Decrease</button>
  <button id="resetbutton">Reset</button>
  <button id="increasebutton">Increase</button>
</div>
```

---

## 🖼️ Demo
Open the `counter program.html` file in your browser to view the live demo.

---

## 📚 Learning Objectives
- Understand DOM manipulation with `document.getElementById()`.  
- Learn event-driven programming using JavaScript’s `onclick`.  
- Practice responsive UI styling using CSS.

---

## 🧑‍💻 Author
**Belal Mohamed Fathy Sayed Nasr**  
📧 [belalnasract@gmail.com](mailto:belalnasract@gmail.com)  
🌐 [GitHub Profile](https://github.com/Belal6205)

---
**⭐ Don’t forget to star this repo if you found it helpful!**
````

