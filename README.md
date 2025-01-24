# 🌟 Sample Blog Website & Login Page with Sign Up 🚀

Welcome to the **Sample Blog Website & Login/Sign-Up Page** project! This repository consists of two major sections:

1. **Sample Blog Website** - A blog page with a navigation bar, smooth transitions, and interactive post filtering.

2. **Login & Sign-Up Page** - A modern and animated login page that allows users to sign in and sign up with a smooth transition effect.

---

## 📦 Table of Contents

1. [Project Overview](#project-overview)

2. [Features](#features)

3. [Installation](#installation)

4. [Usage](#usage)

5. [How It Works](#how-it-works)

6. [Technologies Used](#technologies-used)

7. [File Structure](#file-structure)

8. [Screenshots](#screenshots)

9. [Demo](#demo)

10. [Contributing](#contributing)

11. [Contact](#contact)

---

## 📝 Project Overview

This project combines a **Sample Blog Website** with a **Login & Sign-Up Page**. Both sections provide a smooth user experience, responsive design, and modern UI, and are designed to be user-friendly and visually appealing. 

The blog section includes a dynamic filterable grid of posts, where users can filter content by category. The login page provides a seamless transition between **Sign In** and **Sign Up** forms with social media sign-in options.

---

## 🚀 Features

### **Sample Blog Website**:

- **Interactive Blog Post Filtering**: Users can filter blog posts based on categories (e.g., All, Web Development, Design, etc.). This provides an interactive way to sort and view content.

- **Sticky Navigation Bar**: The navbar becomes sticky as the user scrolls down the page, providing a consistent and always accessible navigation experience.

- **Smooth Post Transitions**: Post filtering happens with a smooth fade-in and fade-out effect for an elegant UI/UX.

- **Responsive Design**: The layout is fully responsive and adjusts seamlessly to different screen sizes, ensuring it looks great on mobile, tablet, and desktop devices.
  
### **Login & Sign-Up Page**:

- **Modern Sign-In and Sign-Up Forms**: The page displays **Sign In** and **Sign Up** forms. The **Sign Up** form appears with a smooth animation when toggled.

- **Smooth Transition Effects**: The transition between **Sign In** and **Sign Up** forms is smooth and visually appealing, giving a polished feel.

- **Social Media Sign-In**: Users can choose to sign in or sign up using popular platforms like Facebook, Twitter, Google, and Instagram.

- **Responsive Design**: The forms adapt to different screen sizes, offering a mobile-first experience that looks great on all devices.

- **Animated Background**: The background of the page features a modern gradient effect and transitions smoothly as users interact with the forms.

---

## ⚙️ Installation

To get started with this project on your local machine, follow these steps:

### Prerequisites:

Ensure you have a modern browser (such as Chrome, Firefox, or Edge) to open and interact with the page.

### Steps to Install:

1. **Clone the repository**:
   
   ```bash
   git clone https://github.com/sudhanshu-j/sample-blog-login-webpage.git
   ```

2. **Navigate to the project directory**:
  
  ```bash
  cd sample-blog-login-webpage
  ```

3. **Open the files**: Open the `index.html` for the Sample Blog Website and the `login.html` for the Login/Sign-Up Page in your preferred browser.

You can open them by either double-clicking on the HTML files or by right-clicking and selecting "Open with" and choosing your browser.

---

## 🖥️ Usage

### **Sample Blog Website:**

- **Home Page**: On visiting the blog page, you will see a grid layout of blog posts.

- **Filter Posts**: You can filter posts by categories such as “All”, “Web Development”, “Design”, etc. When you click a category, only the relevant posts will appear.

- **Sticky Navbar**: As you scroll down, the navigation bar will stick to the top of the screen, with a shadow effect to indicate that it is now fixed at the top.

- **Mobile Responsiveness**: Resize your browser window to test the responsive behavior. The layout adjusts according to different screen sizes.

### **Login & Sign-Up Page:**

- **Sign In Form**: The default form displayed when the page loads is the Sign In form.

- **Sign Up Form**: Clicking the Sign Up button smoothly animates the form transition to show the Sign Up form.

- **Switch Between Forms**: You can toggle between Sign In and Sign Up using their respective buttons.

- **Social Media Login**: The login page includes icons for Facebook, Twitter, Google, and Instagram for social login.

- **Mobile Responsiveness**: The layout adjusts perfectly for mobile screens. The forms stack vertically and the background becomes a smooth gradient.

---

## 🔑 How It Works

### **Sample Blog Website:**

- **HTML Structure**:  
   The page structure is divided into sections like the header (with navigation), the main content (with blog posts), and the footer. Each blog post is contained within a `<div>` that holds the title, content, and a category for filtering.

- **CSS Styling**:  
   The blog layout is built using Flexbox and Grid systems to ensure it’s responsive and adapts to different screen sizes. The navbar becomes sticky with CSS on scroll, and the filtering of posts uses smooth transitions.

- **JavaScript/jQuery**:  
   The filtering functionality is implemented using jQuery. When a filter button is clicked, jQuery is used to hide and show the relevant posts, along with a smooth transition effect. The sticky navbar effect is controlled using JavaScript to toggle the shadow class when the page is scrolled.

### **Login & Sign-Up Page:**

- **HTML Structure**:  
   The page is divided into two main forms, Sign In and Sign Up. Each form contains the necessary fields: username, password, and email for the sign-up form.

- **CSS Styling**:  
   The forms are styled with rounded inputs and a modern gradient background. Hover effects are added to buttons and social media icons. The page background uses a circular gradient effect that transitions when switching between the sign-up and sign-in forms.

- **JavaScript**:  
   The transition between the Sign In and Sign Up forms is achieved by toggling the `sign-up-mode` class on the container element, which animates the transition of the forms. The social media login buttons are designed with hover effects, and clicking them simulates a social login action.

---

## 🛠️ Technologies Used

- **HTML5**: Used for structuring the content of the page, including the forms, posts, and layout elements.

- **CSS3**: Applied for all styling, including layout, color schemes, gradients, animations, and transitions.

- **JavaScript**: Used to handle the dynamic functionality such as form transitions and blog post filtering.

- **jQuery**: Utilized to filter blog posts and add smooth animations.

- **Font Awesome**: For social media icons (Facebook, Twitter, Google, Instagram) used in the login page.

- **Google Fonts**: Used the "Playfair Display" font to provide an elegant and readable typography.

---

## 📂 File Structure

```bash
├── index.html                # Main blog page with post filtering
├── login.html                # Login page with Sign In and Sign Up forms
├── style.css                 # Styles for both blog page and login page
├── script.js                 # JavaScript logic for blog post filtering and form transitions
└── images/
    ├── blog-filter.png       # Example image for blog post filtering
    ├── sign-in.png           # Example image for the Sign In page
    ├── sign-up.png           # Example image for the Sign Up page
    └── social-login.png      # Example image for social login buttons
```

---

## 🎥 Demo

You can view the live demo of this project by visiting the following link:

[Live Demo](https://techtrends-today.netlify.app/)

---

## 🤝 Contributing

We welcome contributions! To contribute to this project, follow these steps:

### Steps to contribute:

1. **Fork the repository** by clicking the "Fork" button at the top right of this page.

2. **Clone your forked repository** to your local machine:
    ```bash
    git clone https://github.com/your-username/sample-blog-login-webpage.git
    ```
3. **Create a new branch**:
    ```bash
    git checkout -b feature-branch
    ```
4. **Make your changes and commit**:
    ```bash
    git commit -am 'Add new feature or fix'
    ```
5. **Push to your branch**:
    ```bash
    git push origin feature-branch
    ```
6. **Create a Pull Request** to merge your changes into the main repository.

---


## 💬 Contact

If you have any questions or suggestions, feel free to reach out by opening an issue or contacting me directly:

📧 sudhanshujha164@gmail.com
