# 📝 Simple Blog Application with MongoDB

This blog app is built with **Node.js**, **Express**, **EJS**, and **MongoDB** using **Mongoose**. It uses `app.get()` for navigation and `app.post()`
for submitting posts. Blog posts are stored in MongoDB and displayed on the home page. Perfect for learning server-side rendering, routing, and
database integration in Express.

## ✨ Features

- 🔄 **Page Navigation**: Uses `app.get()` to handle HTTP GET requests for navigating between different pages.
- 📝 **Post Submission**: Utilizes `app.post()` to submit new blog posts through a form.
- 🆔 **Access Posts by ID**: The application allows users to access individual blog posts by their unique ID. When a blog post is submitted, it is
  stored in MongoDB with a unique \_id. Users can view a specific post by navigating to `/posts/:postId`, where `:postId` is replaced by the actual ID
  of the post.
- 🗄️ **MongoDB Integration**: Blog posts are stored in MongoDB using Mongoose, enabling data persistence.
- 📜 **Real-Time Updates**: Submitted posts are stored in the database and displayed on the home page.

## 🛠️ Technologies Used

- ![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
- ![Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
- ![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
- ![EJS](https://img.shields.io/badge/EJS-F9DB24?style=for-the-badge&logo=ejs&logoColor=000)
- ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
- ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/iamshbr/Simple-Blog-App-2.git
   ```
