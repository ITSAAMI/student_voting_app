# 🎓 Student Task Voting System

A clean, minimal, classroom-friendly web application built using **HTML**, **CSS**, **Bootstrap 5**, and **Vanilla JavaScript**.
The app allows teachers or group leaders to **create quick voting tasks** and randomly select a student for any responsibility (e.g., *washing utensils*, *cleaning the class*, *arranging chairs*, etc.).

---

## 🚀 Features

### ✔ Create Custom Voting Tasks

* Add any task title (e.g., “Today’s Class Cleaning”).
* Use pre-built shortcuts for quick selection (Utensils, Class Cleaning, Chairs, Discipline, etc.).

### ✔ Add Students Easily

* Add student names dynamically.
* Names appear as tags/badges.
* Remove any student instantly.
* Data is saved in **localStorage** so the list stays even after page refresh.

### ✔ Smart Random Selection

* Press **Start Voting** and a smooth “processing” animation appears.
* A random student is chosen using a fair algorithm.
* A minimal confetti celebration plays to highlight the winner.

### ✔ Voting History

* Every saved vote is stored in localStorage with:

  * Task Name
  * Winner Name
  * Date & Time
* History section displays all previous records in clean list format.

### ✔ Clean, Beautiful UI/UX

* Bootstrapped layout with soft shadows and rounded cards.
* Minimalistic design made for classrooms and clean projection.
* Smooth fade-in animations using **Animate.css**.
* Perfect for mobile, tablet, and desktop.

---

## 🛠️ Tech Stack

| Technology            | Purpose                       |
| --------------------- | ----------------------------- |
| **HTML5**             | Structure                     |
| **CSS3**              | Styling                       |
| **Bootstrap 5**       | UI components & layout        |
| **JavaScript (ES6+)** | Logic & functionality         |
| **localStorage API**  | Saving data persistently      |
| **Animate.css**       | UI animations                 |
| **Canvas-Confetti**   | Winner celebration animations |

---

## 📦 Project Structure

```
/
├── index.html     # Main project file (all-in-one)
├── README.md      # Documentation (this file)
└── assets/        # (optional) future images/icons
```

Currently, the project is single-file (HTML/CSS/JS in one place), very simple to clone and run.

---

## 🔧 How to Run Locally

1. Clone the repository

   ```bash
   git clone https://github.com/ITSAAMI/student_voting_app.git
   ```

2. Open the folder:

   ```bash
   cd student-voting-app
   ```

3. Run the project by simply opening **index.html** in any browser.

> 💡 No dependencies, no build tools — 100% front-end and offline-friendly.

---

## 🎉 Live Demo

If you're planning to host it (e.g., GitHub Pages):

```
https://github.com/ITSAAMI/student_voting_app
```

---

## 📌 Future Enhancements (Optional)

* Dark Mode toggle
* Export history to CSV
* Student profile pictures
* Multi-winner selection
* Better animations using GSAP
* Firebase login
* Cloud database for shared voting

---

## 👨‍🏫 Created By

**Amir Hayat**

* Web Developer & Instructor
* Logic Gigs Pvt. Ltd.
* Contact: **03119899940**
* Email: **[itsaami42@gmail.com](mailto:itsaami42@gmail.com)**
