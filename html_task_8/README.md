# 🌍 GT Holidays – Travel & Tour Packages

## 📌 Project Overview

**GT Holidays – Travel & Tour Packages** is a travel website webpage developed using **HTML5 and Tailwind CSS**. The project showcases popular tour packages, a travel enquiry form, customer testimonials, office locations, contact information, and social media links.

The website is designed to provide users with an overview of travel packages and a simple form to enquire about their dream vacation.

This project was created to practice HTML structure, Tailwind CSS utility classes, grid layouts, forms, images, and webpage design.

---

## ✨ Features

* 🌍 Popular domestic and international tour packages
* 💑 International honeymoon packages
* 🇪🇺 Europe tour packages
* 🎓 Educational tour packages
* 📩 Travel enquiry and booking form
* 👤 Personal information input fields
* 📅 Travel date selection
* 👥 Number of travellers input
* 🏖️ Vacation type selection
* 📞 Contact information section
* 💬 Customer testimonial cards
* 🏢 Corporate office and head office details
* 📍 Branch locations across India
* 📱 Social media icons
* 🎨 Tailwind CSS styling
* 📐 CSS Grid layouts

---

## 🛠️ Technologies Used

* **HTML5** – Webpage structure
* **Tailwind CSS** – Styling and layout
* **CSS Grid** – Organizing content into columns
* **HTML Forms** – Collecting travel enquiry details
* **HTML Input Elements** – Accepting user information
* **HTML Select Element** – Selecting vacation types

---

## 📄 Website Sections

### 1. Popular Packages

Displays images representing different travel package categories:

* India Tour Packages
* International Tour Packages
* International Honeymoon Packages
* Europe Tour Packages
* Educational Tour Packages

### 2. Stay Connected

Displays contact information to help visitors connect with the travel company.

### 3. Travel Enquiry Form

The form collects the following information:

* Name
* City of Residence
* Email
* Phone Number
* WhatsApp Number
* Travel Destination
* Date of Travel
* Number of People
* Vacation Type

Available vacation types include:

* Honeymoon
* Friends Trip
* Family Trip
* Corporate Trip

**Note:** The current form is a frontend implementation. It does not include backend processing or database storage.

### 4. Customer Testimonials

Displays customer feedback about the company's travel services and holiday planning experience.

### 5. Office Locations

Includes corporate office and head office information, along with a list of branch cities such as Chennai, Bangalore, Coimbatore, Salem, Mumbai, Hyderabad, and others.

### 6. Contact and Social Media

The footer displays:

* Phone number
* Email address
* Facebook icon
* Instagram icon
* YouTube icon
* LinkedIn icon

---

## 🎨 Tailwind CSS Concepts Used

| Tailwind Class  | Purpose                         |
| --------------- | ------------------------------- |
| `grid`          | Creates a CSS Grid layout       |
| `grid-cols-2`   | Creates two columns             |
| `grid-cols-3`   | Creates three columns           |
| `gap-5`         | Adds spacing between grid items |
| `p-5`           | Adds padding                    |
| `ml-10`         | Adds left margin                |
| `mt-25`         | Applies top margin              |
| `text-2xl`      | Sets large text size            |
| `font-serif`    | Applies a serif font            |
| `text-white`    | Sets white text color           |
| `bg-black`      | Sets a black background         |
| `bg-yellow-500` | Applies a yellow background     |
| `rounded-xl`    | Rounds element corners          |
| `shadow-lg`     | Adds a large shadow             |
| `border-2`      | Adds a border                   |
| `text-justify`  | Justifies text                  |
| `w-10` / `h-10` | Sets element dimensions         |

---

## 📁 Project Structure

```text
GT-HOLIDAYS/
│
├── index.html
├── README.md
│
├── images/
│   ├── India-Tour-Packages.webp
│   ├── International-Tour-Package.webp
│   ├── International-Honeymoon-Packages.jpg
│   ├── Europe-tour-package.webp
│   ├── Educational-Tour-Packages.webp
│   └── map-pg.jpg
│
└── png/
    ├── phone-call.png
    ├── email.png
    ├── facebook.png
    ├── instagram.png
    ├── youtube.png
    └── linkedin.png
```

*This is a suggested folder structure. Update the filenames to match your actual project files.*

---

## 🚀 How to Run the Project

### Step 1: Download or Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### Step 2: Open the Project Folder

Navigate to the folder containing `index.html`.

### Step 3: Run the Website

Open `index.html` in a web browser such as Google Chrome or Microsoft Edge.

### Step 4: View the Website

Explore the tour package gallery, travel enquiry form, testimonials, office details, and footer.

**Internet connection is required** to load Tailwind CSS from the CDN used in the HTML file.

---

## 🖼️ Important Note About Image Paths

The current code uses Windows-specific image paths, such as:

```text
C:\Users\ADMIN\Desktop\HT\India-Tour-Packages-770x375.webp
```

These paths will not work on other computers or after deploying the project online.

Store the images inside your project directory and use relative paths instead:

```html
<img
  src="images/India-Tour-Packages-770x375.webp"
  alt="India Tour Packages"
  class="rounded-xl"
>
```

For the background image, use:

```html
<div
  style="background-image: url('images/map-pg.jpg');
         background-repeat: no-repeat;
         background-size: cover;"
>
```

Make sure the image filenames and folder names match the paths in your HTML.

---

## 🎯 Learning Objectives

This project helps demonstrate practical knowledge of:

* HTML webpage structure
* Tailwind CSS utility classes
* CSS Grid layouts
* Image galleries
* HTML forms and input fields
* Dropdown selection elements
* Spacing and typography
* Customer testimonial layouts
* Footer and contact information design
* Organizing frontend project assets

---

## 🔮 Future Improvements

Possible improvements include:

* Responsive layouts for mobile, tablet, and desktop
* Navigation bar with working links
* Interactive tour package cards
* Form validation using JavaScript
* Functional booking enquiry submission
* Backend integration for storing enquiries
* Dynamic tour package filtering
* Improved customer testimonial cards
* Clickable social media icons
* Better accessibility and image descriptions
* Deployment using GitHub Pages or Vercel

---

## ⚠️ Disclaimer

This is an educational frontend practice project inspired by a travel and tourism website layout. It is not an official GT Holidays website and is not affiliated with or endorsed by GT Holidays.

---

## 👨‍💻 Author

**Dinesh R**

B.Sc. Information Technology
Full Stack Development Learner

---

## 📜 License

This project was created for **educational and learning purposes**.
