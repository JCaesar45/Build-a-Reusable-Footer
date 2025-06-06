````markdown
# 🧩 Reusable Footer Component (React)

This project is a simple reusable `Footer` component built with React. It's designed to be modular and easy to integrate into any React application. The component contains navigation lists, useful links, and copyright.

---

## ✅ Features

- Functional React component (`Footer`)
- Semantic HTML5 `<footer>` structure
- Three `<ul>` sections with at least two items each
- Three working anchor links (`<a href="#">`)
- Copyright
- Clean and customizable layout

---

## 📦 Installation & Usage

### 1. Clone the repository

```bash
git clone https://github.com/your-username/reusable-footer.git
cd reusable-footer
```

### 2. Open or link `index.jsx` in your React project

If you're using it standalone with HTML + Babel setup (like in a CodePen or sandbox):

### 3. File Structure

```
.
├── index.jsx       # Contains the exported Footer component
├── index.html      # Entry point using ReactDOM.render()
└── styles.css      # Optional CSS styles for layout
```

---

## 🧪 Testing Criteria

The Footer component passes the following user stories/tests:

* [x] Exports a React component named `Footer`
* [x] Returns a single `<footer>` element
* [x] Contains three `<ul>` elements, each with two `<li>` items
* [x] Includes a `<p>` element with a © symbol
* [x] Contains three `<a>` tags with `href="#"` and visible text

---

## 📚 Example Output

```html
<footer>
  <ul>
    <li>About Us</li>
    <li>Careers</li>
  </ul>
  <ul>
    <li>Help Center</li>
    <li>Contact</li>
  </ul>
  <ul>
    <li>Terms</li>
    <li>Privacy</li>
  </ul>

  <div>
    <a href="#">Facebook</a>
    <a href="#">Twitter</a>
    <a href="#">LinkedIn</a>
  </div>

  <p>© 2025 Jordan Leturgez. All rights reserved.</p>
</footer>
```

---

## 🛠️ Customization

You can customize:

* List content
* Link text/icons
* Styles via `styles.css` or styled-components
* Replace text links with icons (Font Awesome, Material Icons, etc.)

---

## 📄 License

This project is open-source and free to use under the [MIT License](LICENSE).

```
