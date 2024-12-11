---

### **Blog Page App README**

# Blog Page App

The Blog Page app is a simple, static web application that allows users to read and view blog posts. It features a clean and responsive design built using HTML and CSS, providing a user-friendly interface for exploring blog content.

---

## **Features**
- View a list of blog posts with titles, descriptions, and a "Read More".
- Responsive design that adapts to different screen sizes.
- Clean and simple UI for easy navigation.
- No backend; data is statically rendered in HTML.

---

## **Tech Stack**
- **Frontend**: HTML, CSS
- **Deployment**: Vercel (Static Hosting)

---

## **How to Run Locally**

### **1. Clone the Repository**

```bash
git clone https://github.com/Prakashkumar88/Blog-Page.git
cd Blog-Page
```

### **2. Install Dependencies**

Since this is a static website, no dependencies are needed for running it locally. You can simply open the `index.html` file in your browser.

### **3. Run the Frontend**

To run the site locally, open `index.html` in your web browser.

---

## **Deployment**

Deployed using Vercel. Visit:  
[Frontend Deployment](https://blog-page-seven-fawn.vercel.app)

---

## **Directory Structure**

```
Blog-Page/
│
|── index.html         # Main HTML file
│── style.css          # CSS styling for the app
│
├── .gitignore             # Git ignore file
└── README.md              # Project documentation
```

---

## **Adding New Blog Posts**

To add a new blog post:
1. Open the `index.html` file.
2. Copy and paste the structure for a new post in the blog section.
3. Update the title, description, and link to the full post (if applicable).

Example post structure in HTML:

```html
<div class="blog-post">
  <h2>Blog Post Title</h2>
  <p class="description">Short description of the blog post.</p>
  <a href="#">Read More</a>
</div>
```

---

## **Troubleshooting**

### **Images Not Loading**
- Ensure that the image linkes are placed correctly and refered properly in the HTML.

---

## **Contributing**

We welcome contributions to improve the Blog Page app. To contribute:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-name`.
3. Make your changes and commit: `git commit -m 'Add new feature'`.
4. Push to your fork: `git push origin feature-name`.
5. Submit a pull request.

---

## **License**

This project is licensed under the MIT License. Feel free to use and modify it as needed.

---

Let me know if you need further details or modifications!
