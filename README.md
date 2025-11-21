# **Protocol — Official CSE Dept Club Website**

This is the official website for **Protocol**, the Computer Science Engineering club of **BMS College of Engineering (BMSCE)**.
It includes all public information, events, core team members, and **Synergy Weekly**, the club’s weekly tech newsletter.

---

## 🚀 **Features**

### **🌐 Fully responsive multi-page website**

* Home
* About
* Core Team
* Events
* Synergy Weekly
* Contact

### **📰 Synergy Weekly**

* Dynamic article loading using `synergy.js`
* Featured article logic
* 16:9 thumbnails
* Pink hover highlight + smooth animations

### **📅 Events Section**

* Auto-arranged grid (3 per row)
* A3 portrait posters
* Pink divider, pastel shadows, never-cropped posters
* Easy to add new events through `events.js`-style array

### **👤 Core Team Page**

* 3-per-row centered layout
* Perfect square photos with consistent hover styling

### **🎨 Consistent Design System**

* Antonio & Pacifico fonts
* Protocol pink palette
* Dark theme UI
* Matching navbar + footer on all pages

---

## 📂 **Project Structure**

```
/
│── index.html
│── about.html
│── core.html
│── events.html
│── synergy.html
│── contact.html
│── styles.css
│── script.js
│── synergy.js
│── data/
│     ├── images, posters, thumbnails, etc.
│
└── README.md
```

---

## 🔧 **How to Add Articles (Synergy Weekly)**

Edit **`synergy.js`**, and inside the `articles[]` array, add:

```js
{
  title: "Title Here",
  image: "./data/26.png",
  description: "Short description here",
  url: "https://www.linkedin.com/your-article"
}
```

> Newest articles must be added **to the top** of the array.

---

## 🎉 **How to Add Events**

Inside your `events` array (events.js or inline in events.html):

```js
{
  title: "Event Name",
  date: "Jan 2025",
  image: "./data/events/event01.png",
  description: "3–4 line description about the event."
}
```

> Newest events appear at the top automatically.


---

## 🤝 **Contributions**

This is a student-run website built for BMSCE’s Protocol Club.
Features and improvements are welcome through pull requests.

---
