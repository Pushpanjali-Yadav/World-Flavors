# ⏱️ World of Flavour-Explore Recipe, watch detail Video

World of Flavours is a recipe-based web application that provides users with an interactive platform to explore, search, and learn cooking recipes from around the world.


[![Bootstrap](https://img.shields.io/badge/UI-Bootstrap-7952B3)](https://getbootstrap.com/)
[![Status](https://img.shields.io/badge/Status-Active-success)](#)

---

## 📑 Table of Contents

- [About the Project](#-about-the-project)
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Project Structure](#-project-structure)
- [Design Choices](#-Design-Choices)
- [Live Demo](#-live-demo)
- [Installation](#-installation-for-developers--cs50-staff)
- [Usage](#-usage)
- [Screenshots](#-screenshots)
- [Future Improvements](#-Future-Improvements)
- [Contributing](#-contributing)
- [Reflections](#-Reflections)
- [Contact](#-contact)

---

## 📖 About the Project

World of Flavours is a recipe-based web application that provides users with an interactive platform to 
explore, search, and learn cooking recipes from around the world. The system integrates TheMealDB API and 
YouTube API to fetch meal details, cooking instructions, and video tutorials, making it an engaging and user
friendly recipe hub. 

In this application, users can browse recipes by area (country), category (meal type), or directly search for 
specific dishes. Each recipe comes with step-by-step instructions, ingredients list, cooking process, and an 
embedded video guide. 

The application ensures a smooth user experience with a responsive interface built using HTML, CSS, 
Bootstrap, and JavaScript, while APIs ensure real-time dynamic data fetching. Hosting on GitHub Pages makes 
the project easily accessible. 

This project reflects my learning journey throughout Deepanshi Software Soluion, where I applied concepts of  HTML, CSS, JavaScript, Bootstrap,API integration and Git into a real-world application.

---

## 🚀 Features

- ✅ Provides recipes from multiple cuisines worldwide.
- ✅ Step-by-step instructions and ingredient lists. 
- ✅ Embedded video tutorials for better learning.
- ✅ Responsive design for mobile and desktop users.
- ✅ Real-time dynamic updates via APIs.
- ✅ Easy navigation with categorized browsing.

---

## 🛠 Tech Stack

- **Backend:** Youtube API Key 
- **Frontend:** HTML, CSS, JavaScript, Bootstrap  
- **Database:** MealDB  

---

## 📂 Project Structure

```plaintext
WORLD_FLAVOURS/
│
├── index.html                # Main Flask application
├── dishes.html           # SQLite database
├── SS/                   # Screenshots of my web application
│
├── templates/            # HTML templates
│   ├── layout.html
│   ├── index.html
│   ├── register.html
│   └── dashboard.html
│
├── static/               # CSS, JavaScript, images
│   ├── images/            # It contains all emoge and images
│   ├── style.css 
│   └── heatmap.js
│
├── README.md             # Project documentation
└── requirements.txt      # Dependencies

```

## 💡 Design Choices

### When designing World of Flavours, I had to make several important decisions:

### 1. Centralized & Dynamic Recipe Access 

Through TheMealDB API, the platform retrieves real-time recipes, meal details, and 
ingredients. Eliminates dependency on manual updates, ensuring continuous freshness and variety.

### 2. Frontend Framework

Instead of building everything from scratch, I used Bootstrap to ensure responsiveness across devices. This decision allowed me to focus more on functionality rather than raw CSS design.

### 3. Habit Visualization

For tracking, I debated between bar charts and a calendar heatmap. I settled on the GitHub-style heatmap because it conveys streaks and consistency more effectively than a traditional chart.

### 5. User-Friendly Features 

Search Recipes by meal name. Browse by Category (e.g., Dessert, Seafood, Vegetarian). Browse by Cuisine/Area (e.g., Italian, Indian, Mexican).Detailed Meal Page with image, instructions, ingredients, and video..

---

## 🌐 Live Demo

Check out the live version of the **World Of Flavours** here:  
👉 [Habit Heatmap Tracker](https://pushpanjali-yadav.github.io/World-Flavors/)

---


## ⚡ Installation (For Developers / Contributers)

If you want to run the project locally, follow these steps:

1. **Clone the repository**
```bash
git clone https://github.com/Pushpanjali-Yadav/World-Flavors.git
cd World-Flavours
```

---

## 🎯 Usage

Once **World of flavours** is web application  opened in the browser, you can use it as follows:

1. **Click on start exploring**
   - You can see varoius food categories.

2. **After selecting any category**
   - You can see the list of meals related to that particular category and nav bar is  also show all category
   - You can search by area name with the help of nav bar.

3. **After click on specific meal**
   - You can see the full detail about that particular meal.
   - Full video to make it is also available for every dish.
   - Click on Youtube icon to explore the expert recipe tutorial.
    

4. **Expert Recipe Gallary**
   - Click on any channel to watch that particular expert videos.


---

📌 Example workflow:
- Explore now →  "Pasta" Search/Select → Dish → Show detail.

## 🖼 Screenshots

### 1. Homepage / Landing Page
![Homepage](SS/S1E.png)
*Clean and simple landing page introducing the Habit Heatmap Tracker.*

---

### 2. User Registration & Login
![Register](SS/RLE.png)
*Secure user registration and login system with hashed passwords.*

---

### 4. Add & Manage Habits
![Add Habits](SS/S4.png)
*Easily add new habits and track them over time.*

---

### 3. Dashboard – Heatmap View
![Dashboard](SS/S3.png)

---

### 2. Task Complition visualization

![Dashboard](SS/SLE.png)
*Colorful heatmap Progress bar showing daily habit progress and heighest sticks as well as current stick.*

---

## 📊 Future Improvements

- User Accounts & Favorites.

- AI-Based Recommendations.

- Recipe Upload Feature.

- Mobile App Version.

--- 

## 🤝 Contributing
The project titled as World of Flavours was deeply studied and carefully analyzed to design, code, and implement successfully. And open for contribution.


To contribute:
1. Fork the repository
2. Create a new branch (`git checkout -b feature-name`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature-name`)
5. Open a Pull Request

---

## 📜 Reflections

*The project titled as World of Flavours was deeply studied and carefully analyzed to design, code, and 
implement successfully. It was developed under proper guidance, keeping in mind the current requirements 
and user expectations. All the essential functionalities such as browsing meals, viewing detailed recipes, 
integrating YouTube cooking tutorials, and managing categories/areas have been effectively taken care of 
during the project. *


## 📬 Contact
👩‍💻**Name:  Pushpanjali Yadav**

[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](05pushpanjali@gmail.com) 05pushpanjali@gmail.com

[![GitHub](https://img.shields.io/badge/-GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/Pushpanjali-Yadav) https://github.com/Pushpanjali-Yadav


[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)]((https://www.linkedin.com/in/pushpanjali-yadav-375a172b8/))
[Pushpanjali Yadav](https://www.linkedin.com/in/pushpanjali-yadav-375a172b8/)

## If you liked this project, don’t forget to ⭐ the repo!
