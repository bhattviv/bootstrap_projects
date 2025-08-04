# 🚀 Bootstrap Projects

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)](https://getbootstrap.com/)

A collection of beginner-to-intermediate level frontend projects built using **HTML5**, **CSS3**, and the **Bootstrap 5 framework**. This repository is created for learning, practicing, and showcasing modern responsive web design.

---

## 🔥 Projects Included

| Project No. | Project Name         | Description                                      |
|-------------|----------------------|--------------------------------------------------|
| 01          | Product Landing Page | A responsive product showcase landing page.      |
| 02          | Portfolio Website    | A personal portfolio template with smooth scroll.|
| 03          | Startup Page         | A startup-themed homepage using Bootstrap grid.  |
| 04          | Login Page UI        | A clean and minimal login form using Bootstrap.  |

---

## 🛠️ Tech Stack

- **HTML5**
- **CSS3**
- **Bootstrap 5**
- Responsive Web Design Principles

---

## 📁 Folder Structure

```bash
bootstrap_projects/
│
├── Bootstrap-Project-01/
│   └── index.html
│   └── style.css
│
├── Bootstrap-Project-02/
│   └── index.html
│   └── images/
│
└── ...


## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/bhattviv/Bootstrap-Projects.git
   ```

2. Navigate to any project folder to explore the code

3. Open the HTML files in your browser to see the Bootstrap projects in action

4. Bootstrap is included via CDN in most projects:
   ```html
   <!-- Bootstrap CSS -->
   <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
   
   <!-- Bootstrap Bundle with Popper -->
   <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
   ```

## 💡 Usage Examples

### Responsive Grid System

```html
<div class="container">
  <div class="row">
    <div class="col-md-8">
      <h2>Main Content</h2>
      <p>This area takes up 8 columns on medium screens and above.</p>
    </div>
    <div class="col-md-4">
      <h3>Sidebar</h3>
      <p>This area takes up 4 columns on medium screens and above.</p>
    </div>
  </div>
</div>
```

### Bootstrap Component Customization

```html
<!-- Custom styled card component -->
<div class="card shadow-lg border-primary mb-4">
  <div class="card-header bg-primary text-white">
    <h5 class="card-title mb-0">Featured Content</h5>
  </div>
  <div class="card-body">
    <p class="card-text">Some quick example text to build on the card title.</p>
    <a href="#" class="btn btn-outline-primary">Learn More</a>
  </div>
  <div class="card-footer text-muted">
    Last updated 3 mins ago
  </div>
</div>
```

### Modal Dialog

```javascript
// JavaScript for triggering Bootstrap modal
document.addEventListener('DOMContentLoaded', function() {
  const modalTrigger = document.getElementById('launchModal');
  
  modalTrigger.addEventListener('click', function() {
    const myModal = new bootstrap.Modal(document.getElementById('exampleModal'));
    myModal.show();
  });
});
```

## 📚 Bootstrap Learning Path

This repository demonstrates progression of Bootstrap skills:

1. **Basics** - Grid system, typography, and core components
2. **Intermediate** - Custom theming, component combinations, and utilities
3. **Advanced** - Sass customization, JavaScript interactions, and advanced layouts
4. **Expert** - Building design systems based on Bootstrap, performance optimization

## 🛠️ Technologies Used

- Bootstrap 5
- HTML5
- CSS3/Sass
- JavaScript
- jQuery (for older Bootstrap projects)
- Bootstrap Icons
- Bootstrap Themes

## 🤝 Contributing

Contributions, suggestions, and feedback are welcome! Feel free to open an issue or submit a pull request with your own Bootstrap examples.

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

## 📞 Contact

- GitHub: https://github.com/bhattviv
- if You Want to contact me here is the mail:- 26bhattvivekgmail.com

---

⭐ **Star this repository if you find these Bootstrap projects helpful!**. 
