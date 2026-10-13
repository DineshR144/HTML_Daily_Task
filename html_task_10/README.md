# The Times of India – News Website UI

## 📌 Project Overview

**The Times of India – News Website UI** is a beginner-friendly web development project built using HTML5 and CSS3. It recreates a newspaper-style webpage inspired by The Times of India, displaying news headlines, entertainment content, movies, gaming, sports, and other popular topics.

The webpage uses a multi-column layout to organize images, headings, and descriptions into different content sections.

## ✨ Features

* **Newspaper-Style Header** – Displays the Times of India title.
* **Navigation Bar** – Includes categories such as TOI+, Videos, City, India, World, Business, Technology, Cricket, Sports, and Entertainment.
* **Trending Topics** – Displays topics such as stock markets, creator awards, and other popular subjects.
* **Featured News Section** – Presents news headlines with images and descriptions.
* **Entertainment Section** – Includes information about movies such as *Premam* and *Karuppu*.
* **People and Personalities** – Features content about Harshad Mehta and C. Joseph Vijay.
* **Gaming Section** – Displays information about PUBG: Battlegrounds and Rockstar Games.
* **Movie Highlights** – Includes content about *Vaaranam Aayiram* and *Alaipayuthey*.
* **Image Styling** – Uses rounded corners and padding to improve the appearance of images.
* **Custom CSS Classes** – Uses individual classes to control margins, alignment, spacing, and text formatting.

## 🛠️ Technologies Used

* **HTML5** – Structures the webpage using headings, paragraphs, tables, and divisions.
* **CSS3** – Styles the webpage using selectors, margins, padding, text alignment, and rounded corners.

## 📂 Project Structure

```text
Times-of-India-News-Website/
│
├── index.html
├── images/
│   ├── news images
│   ├── movie posters
│   ├── gaming images
│   └── personality images
│
└── README.md
```

*Note: The `images/` folder is a suggested structure. Place your image files inside it and update the image paths in your HTML file.*

## 🚀 How to Run the Project

1. Download or clone this repository.
2. Open the project folder in Visual Studio Code.
3. Make sure all required images are available in the project.
4. Update the image paths in `index.html` to use relative paths.
5. Open `index.html` in your web browser.

You can also use the **Live Server** extension in Visual Studio Code to preview the webpage.

## 🖼️ Image Path Configuration

The current HTML file uses local Windows paths, for example:

```html
<img src="C:\Users\ADMIN\Desktop\HT\3951374.webp" width="300" height="270">
```

These paths work only on a computer where the images exist at those exact locations.

For better portability, organize images inside the project folder and use relative paths:

```html
<img src="images/3951374.webp" width="300" height="270" alt="Featured news">
```

This makes it easier to share the project on GitHub and run it on other computers.

## 📚 Learning Objectives

This project helps beginners practice:

* Creating webpage layouts using HTML.
* Using headings, paragraphs, tables, and `<div>` elements.
* Applying CSS classes and ID selectors.
* Controlling margins, padding, and text alignment.
* Displaying and styling images.
* Organizing content into different sections.
* Building a basic newspaper-style user interface.

## 🔧 Future Improvements

* Make the layout responsive for mobile phones, tablets, and desktops.
* Replace table-based navigation with Flexbox or CSS Grid.
* Add a functional search bar.
* Make navigation links clickable.
* Use reusable CSS classes to reduce repeated styling.
* Improve spacing and alignment without large negative margins.
* Add hover effects and interactive elements.
* Use semantic HTML elements such as `<header>`, `<nav>`, `<main>`, and `<article>`.

## ⚠️ Disclaimer

This is an educational project created for HTML and CSS practice. It is not an official Times of India website and is not affiliated with or endorsed by The Times of India.

## 👨‍💻 Author

**Dinesh R**
