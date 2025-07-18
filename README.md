# **Travel Management System**

A full-stack web application built with **PHP**, **MySQL**, and **Bootstrap** that enables users to explore travel packages and submit booking enquiries. Designed with modular code structure and clean UI for a smooth user experience.

---

## **🧰 Tech Stack**

- **Frontend:** HTML5, CSS3, Bootstrap  
- **Backend:** PHP (procedural)  
- **Database:** MySQL  
- **Version Control:** Git & GitHub  

---

## **✨ Features**

- 📦 **View Packages**: List of available travel packages with images and details  
- 📄 **Package Details**: View more info, itinerary, and pricing  
- 📨 **Enquiry Form**: Submit booking requests (stored in the database)  
- 🧾 **Dynamic Rendering**: All data is fetched from the database using PHP and MySQL

---

## **📐 Architecture Overview**

- `/index.php` - Homepage with package listings  
- `/detail.php` - Single package details view  
- `/enquiry.php` - Form to submit travel enquiries  
- `/function.php` - Reusable backend functions for DB operations  
- `/stylecss.css` - Bootstrap-based custom styling  

---

## **🧠 Technical Challenge Faced**

One of the major challenges was **handling dynamic content rendering and form validation in a multi-page PHP environment**. Initial form submissions lost user input or failed silently.

### **🔧 Solution**

- Used **structured PHP functions** to handle DB interactions and input sanitation  
- Implemented **server-side validation** with persistent form states and feedback messages  
- Debugged issues using browser dev tools, logging, and MySQL query tests  
- Consulted **online communities**, course mentors, and Stack Overflow to refine logic

---

## **🤝 Communication & Collaboration**

I actively documented my work and used GitHub Issues and commits to track progress.  
Whenever I was blocked, I communicated clearly through GitHub Discussions and sought feedback from peers, ensuring quick resolutions and better solutions.

---

## **🧪 Database Tables**

- `packages(id, name, description, price, image_path)`  
- `enquiries(id, name, email, from_date, to_date, message, package_id, submitted_at)`

---

## **🚀 Setup Instructions**

1. Clone the repository  
   ```bash
   git clone https://github.com/yourusername/travel-management-system.git
