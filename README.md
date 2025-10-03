# 🛍️ E-commerce Platform in Next.js

This project was carried out over 4 weeks by a group of four people. The goal was to create a minimalist e-commerce platform built with **Next.js 15 App Router** and **TypeScript**. We created a fictional company and a platform for selling electronics, drawing some design inspiration from Komplett's website. We used Figma to plan the layout and for team referencing. We utilized GitHub Projects to structure and plan the work. The site fetches data from [dummyjson.com/products](https://dummyjson.com/products). We host our website on [Vercel](https://new-tech-beryl.vercel.app/)

---

## 📑 Table of Contents
- 📖 [About the Project](#-about-the-project)
- ✨ [Features](#-features)
- 🛠 [Technologies](#-technologies)
- ⚙️ [Installation](#-installation)
- 🚀 [Usage](#-usage)
- 📂 [Project Structure](#-project-structure)
- 📈 [Workflow](#-workflow)
- 🗓 [Sprint Plan](#-sprint-plan)
- 📚 [Lessons Learned](#-lessons-learned)
- ✍️ [Contact](#-contact)


---

## 📖 About the Project
This was a group exercise with the goal of building a **minimalist e-commerce platform**.
The purpose was to practice:
- Working with Server Components, Client Components, static and dynamic routes
- Handling asynchronous data
- Practical agile teamwork

---

## ✨ Features
- ✅ Homepage with product overview
- ✅ Hero section with CTA
- ✅ Product page with an "Add to Cart" button
- ✅ Shopping Cart
- ✅ Search bar
- ✅ About the company page
- ✅ Contact page with a contact form
- ✅ Admin page for adding, updating, and deleting products

---

## 🛠 Technologies
- [Next.js 15 (App Router)](https://nextjs.org/)
- [WAVE](https://wave.webaim.org/)
- [API](https://dummyjson.com/products)
- [Vercel](https://vercel.com)

---

## ⚙️ Installation
```bash
# Clone the repository
git clone https://github.com/Frawser/new-tech

# Navigate to the project directory
cd new-tech

# Install dependencies
npm install

# Start the development server
npm run dev
```

---

## 🚀 Usage
* Homepage -> displays products + hero section
* About -> static page with text and image
* Contact -> static page with contact form
* Products page -> list of products
* Cart -> ability to add products
* Search bar -> search for products
* Admin -> add, delete, and update products

---

## 📂 Project Structure

```
|-- app/
|  |-- page.tsx            # Home page
|  |-- about/page.tsx      # About us
|  |-- admin/page.tsx      # Admin
|  |-- cart/page.tsx       # Cart
|  |-- contact/page.tsx    # Contact
|  |-- products/page.tsx   # Products
|-- components/            # Reusable components              
|-- lib/utils              # Utils
```

---

## 📈 Workflow

* 👥 Group work in agile sprints (SCRUM)
* 📑 GitHub Projects (Kanban board)
* 🌱 Feature branches
* 🔍 PR + code review

---

## 🗓 Sprintplan

### Sprint 1 - Basic structure

* Set up the Next.js project
* Created menus & static pages
* Hämta data från api:et och rendera enkel lista

### Sprint 2 - Functionality

* Created components such as product card and pagination buttons

### Sprint 3 - Interactivity

* Continued work on components
* Created forms for the admin page
* Fixed things such as ensuring the number above the cart icon updates when the shopping cart is updated

### Sprint 4 - Polish and Responsiveness

* Final adjustments to styling
* Fine-tuned responsiveness
* Created the README file
* Presented the results

---

## 📚 Lessons Learned

* The difference between Server & Client Components in Next.js
* Agile work methods
* API integration with dummyjson
* Responsiveness
* CSS Modules
* Reusable Components
* Vercel hosting
* GitHub Projects

---

## ✍️ Contact

👤 Anders
🔗[anderszone](https://github.com/anderszone)

👤 Karl Ragnar
🔗[presidentkg](https://github.com/presidentkg)

👤 Mikael
🔗[Frawser](https://github.com/Frawser)

👤 Valeriia
🔗[avreally](https://github.com/avreally)

## 💡 Individual Reflection – Anders Johansson

### 🌟 Contribution to the project
My main contributions to the project included creating and improving several core features and ensuring responsive design across devices.  

- Built two static and fully responsive pages:  
  - **About page** with text and team member images  
  - **Contact page** with a contact form
- Implemented **pagination** on the product listing, using both Server and Client Components.  
- Tested and fixed **responsiveness** for mobile, tablet, and desktop devices.  
- Adjusted **responsive styling** by switching between `px` and `rem` units in CSS where needed.  
- Developed a **delete button** with full functionality on the admin page, enabling product removal from the shop.  
- Created a **hamburger menu (mobile navigation)** for smaller screen sizes.

### 🛠 Technologies used
- **Next.js 15** (App router)
- **React concepts:** Reusable components, Hooks, Conditional rendering, Props
- **Next.js concepts:** Server actions, Server & Client components
- **API integration** with DummyJSON  
- **CSS Modules**  
- **Responsive design** (mobile-first, responsive units)
- **HTML5**  
- **TypeScript**

### 🚀 Future development
If I were to continue working on this project, I would prioritize:
- Integrate payment methods: Stripe and PayPal to enable safe online transactions directly using our e-commerce platform.
- Ensure proper form handling and validation for the Contact page.
- Develop a custom backend with a dedicated API and database to handle product management, user data and authentication.
- Implement secure user authentication and authorization (OAuth or JWT).
- Add role-based access control for admin and user roles.
- Improve accessibility (WCAG) by adding aria-attributes, color contrast and font sizes.
- Refactor the codebase to ensure more consistent styling and structure across components.
- Create a system for users to rate and review products, enhancing the shopping experience.  
- Expand the admin panel with additional features such as managing inventory and orders.
- Add unit and integration tests to improve reliability and maintainability.
