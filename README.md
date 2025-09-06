# 🚀 Typed.js Portfolio Demo

This is a demo project built with HTML, CSS, and JavaScript using the [Typed.js](https://github.com/mattboldt/typed.js/) library. It simulates a portfolio intro where skills are typed in real-time, and includes buttons to view GitHub, LinkedIn, and download a resume.

## 👨‍💻 Developed by
**Vikash Kumar Bharti**  
🔍 Aspiring Software Developer | Java | Spring Boot | Web Dev

---

## 🌟 Features

- 🔠 Animated text typing using Typed.js
- 🎨 Custom styled background and layout
- 📄 Resume download button
- 🔗 GitHub and LinkedIn profile buttons
- ✨ Fully responsive and modern UI

---

## 📹 Screenshots Demo
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/06f518a8-281a-4867-a939-04faa02f367b" />


---
▶️ **Demo Video on LinkedIn**: [Watch here](https://www.linkedin.com/posts/vikash-kumar-bharti-44699b294_webdevelopment-frontenddevelopment-typedjs-activity-7370148585302093824-x6HZ?utm_source=share&utm_medium=member_desktop&rcm=ACoAAEdWUbYB4JSFFwIxDL3JvNInnyMMpm0nm3k) *(Update with video link once uploaded)*  

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript (Typed.js)
- Bootstrap Icons

---
Below Typed.js library CDN link and Template code if YOU have doubt then freely DM - [LinkedIn](https://www.linkedin.com/in/vikash-kumar-bharti-44699b294/)
## 🧾 Installation
Typed.js is a library that types. Enter in any string, and watch it type at the speed you've set, backspace what it's typed, and begin a new sentence for however many strings you've set.

Installation
CDN
```<script src="https://unpkg.com/typed.js@2.1.0/dist/typed.umd.js"></script>```
For use directly in the browser via <script> tag:
```
  <!-- Element to contain animated typing -->
  <span id="element"></span>

  <!-- Load library from the CDN -->
  <script src="https://unpkg.com/typed.js@2.1.0/dist/typed.umd.js"></script>

  <!-- Setup and start animation! -->
  <script>
    var typed = new Typed('#element', {
      strings: ['Fist String ', 'Second String ','Third String and so on'],
      typeSpeed: 50,
      backSpeed: 50,
      loop : true,
      typeDelay: 20,
      backDelay: 20
    });
    
  </script>
</body>
```
Clone the repository and run locally:

```bash
git clone https://github.com/VikashBharti0/typedjs-demo.git
cd typedjs-demo
open index.html
