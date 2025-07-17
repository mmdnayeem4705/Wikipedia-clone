## 📚 Wikipedia Clone

A simple Wikipedia search app that uses the [Wikipedia API](https://www.mediawiki.org/wiki/API:Main_page) to fetch and display search results in real-time. Built with vanilla HTML, CSS, and JavaScript, and includes a dark/light theme toggle.

---

### 🚀 Demo

> 🔗 [Live Demo (Optional if hosted on GitHub Pages)](https://your-username.github.io/Wikipedia-clone)

---

### ✨ Features

* 🔍 Search for Wikipedia articles using the Wikipedia API
* 📄 Display results with title, URL, and snippet
* 🌗 Toggle between light and dark themes
* ⚡ Loading indicator while fetching data
* 🛡️ Secure links with `rel="noopener"` and `target="_blank"`

---

### 🛠️ Technologies Used

* **HTML5**
* **CSS3**
* **Vanilla JavaScript (ES6+)**
* [Wikipedia REST API](https://en.wikipedia.org/w/api.php)

---

### 📁 Project Structure

```bash
Wikipedia-clone/
├── index.html
├── style.css
├── script.js
└── README.md
```

---

### 🧪 How to Run Locally

#### 🔁 Clone the repository

```bash
git clone https://github.com/Sivamanikant/Wikipedia-clone.git
cd Wikipedia-clone
```

#### 🧰 Open the app

Just double-click the `index.html` file or open it in your browser:

```bash
# Example using VS Code
code .
# Then right-click index.html and select "Open with Live Server" (if installed)
```

---

### 🧠 How It Works

1. The user enters a query and submits the form.
2. The app fetches search results from Wikipedia’s public API.
3. Each result includes a clickable title, the URL, and a snippet.
4. A loading spinner shows while results are being fetched.
5. A dark/light mode toggle switches the page's theme dynamically.

---

### ⚠️ Known Issues

* Typo in `searchWikipeida` function name (should be `searchWikipedia`)
* `results.pageid` used incorrectly in `displayResults()` — should be `result.pageid`
* Minor styling improvements possible

---

### ✅ To-Do (Optional)

* Add pagination
* Add voice search
* Improve mobile responsiveness
* Debounce input for better UX

---

### 🙌 Acknowledgments

* [Wikipedia API](https://www.mediawiki.org/wiki/API:Main_page)
* [MDN Web Docs](https://developer.mozilla.org/) for web development references

---

### 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

Would you like me to fix the bugs in the script (`searchWikipeida`, `results.pageid`, etc.) and give you the corrected version too?
