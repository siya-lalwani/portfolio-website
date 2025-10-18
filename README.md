# Siya Lalwani - Creative Data Portfolio

![Portfolio Screenshot](https://via.placeholder.com/800x400.png?text=Add+Your+Portfolio+Screenshot+Here)

A creative, quirky, and illustrated personal portfolio website for Siya Lalwani, a data analyst with a passion for blending data with design. This project is built as a single, self-contained HTML file, making it incredibly easy to host and maintain.

**[View Live Demo](https://siya-lalwani.github.io)** *(Replace with your GitHub Pages link)*

---

## ✨ About This Project

This portfolio was designed to be more than just a resume; it's a reflection of a creative personality in the data science field. It avoids a traditional corporate look in favor of a friendly, hand-drawn aesthetic with bold typography, custom doodles, and a vibrant color palette.

The entire project is contained in a single `index.html` file, which requires no complex setup, build tools, or dependencies.

### Key Features

-   **Fully Responsive:** Looks great on desktops, tablets, and mobile phones.
-   **Single-File Architecture:** The entire website is in one `index.html` file. No servers or build steps needed.
-   **Quirky & Illustrated Design:** Custom styles, doodles, and fonts create a unique, memorable look.
-   **Interactive Elements:** Subtle hover effects and a clean layout make for an engaging user experience.
-   **Clear Sections:** Includes sections for Hero, Skills, Projects, Experience, and a Contact footer.

---

## 🛠️ Technologies Used

This project keeps things simple and efficient:

-   **HTML5:** For the core structure and content.
-   **Tailwind CSS (via CDN):** For all styling, enabling a responsive, utility-first approach without needing a local setup.
-   **Google Fonts:** For custom typography (`Inter`, `Bebas Neue`, `Permanent Marker`, `Playfair Display`).
-   **Inline CSS:** For custom design elements that give the portfolio its unique character.

---

## 🚀 Getting Started

Getting this portfolio set up is as easy as it gets:

1.  **Download the Code:** Clone or download the repository to your local machine.
2.  **Open in Browser:** Find the `index.html` file and double-click it to open it in your web browser (like Chrome, Firefox, or Safari).

That's it! The website will run locally without any other steps.

---

## 🎨 How to Customize

To make this portfolio your own, simply open the `index.html` file in a text editor (like VS Code, Sublime Text, or even Notepad) and edit the content directly.

Here’s a guide to the key sections you'll want to change:

### 1. Title & Header

-   **Page Title:** Change the text inside the `<title>` tag in the `<head>` section.
-   **Header Name:** Edit your name in the `<header>` section.

```html
<!-- In the <head> section -->
<title>Your Name | Your Title</title>

<!-- In the <body> section -->
<header>
    <a href="#" class="text-4xl font-extrabold structural-accent quirky-header">
        YOUR <span class="main-accent">NAME</span>
    </a>
</header>
```

### 2. Profile Image

-   Find the `<img>` tags in the `#hero` section. There is one for mobile and one for desktop.
-   Replace the `src="https://via.placeholder.com/..."` URL with a link to your own image, or a local path if you are hosting it with the file (e.g., `src="my-photo.jpg"`).

```html
<!-- Mobile Image -->
<img src="path/to/your/image.jpg" alt="A photo of you" ... >

<!-- Desktop Image -->
<img src="path/to/your/image.jpg" alt="A photo of you" ... >
```

### 3. Hero Section Text

-   Edit the text for your three key strengths in the `#hero` section.

```html
<h3 class="text-3xl main-accent font-bold mt-2 serif-title">Your First Strength</h3>
<p class="text-gray-700 mt-2 text-base">
    Describe your strength here.
</p>
```

### 4. Skills, Projects, and Experience

-   Navigate to the sections with the IDs `#skills`, `#projects`, and `#experience`.
-   All the content is hard-coded in the HTML. Simply find the text you want to change and replace it with your own information.

**Example for a Skill Card:**

```html
<div class="bg-white illustrated-card ...">
    <!-- ... -->
    <h3 class="text-2xl font-bold quirky-header main-accent">Your Skill Category</h3>
    <ul class="text-gray-600 space-y-2 text-lg mt-4">
       <li><strong>Tool 1:</strong> (Description)</li>
       <li><strong>Tool 2:</strong> (Description)</li>
    </ul>
</div>
```

### 5. Contact & Footer

-   Scroll down to the `<footer>` section with the ID `#contact`.
-   Update the `href` in the `<a>` tags to your email and GitHub profile link.

```html
<a href="mailto:your.email@example.com" ...>
    your.email@example.com
</a>
<a href="https://github.com/your-username" ...>
    GitHub Profile
</a>
```

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE). Feel free to use it as a template for your own portfolio.
