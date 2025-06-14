# ☁️ Cloud Storage System

This is a simple cloud storage web application where users can upload files (especially images), which are then stored securely using Cloudinary. Built using Node.js and Express, this project demonstrates how to integrate a cloud-based media storage service.

---

## 📌 Features

- Upload image files using a web UI
- Store images securely on **Cloudinary**
- See uploaded images on a gallery page (if implemented)
- Clean and responsive design
- Error handling and validation

---

## 🛠️ Tools & Technologies Used

- **Frontend**: HTML, CSS, JavaScript (Vanilla)
- **Backend**: Node.js, Express.js
- **Cloud Storage**: Cloudinary
- **Templating (Optional)**: EJS
- **File Upload Handling**: Multer
- **Version Control**: Git & GitHub

---

## 🧠 How It Works

1. User visits the homepage.
2. Uploads an image via a file input form.
3. Image is sent to the backend using POST request.
4. Backend uses `multer` to handle the file, then uploads it to **Cloudinary** via API.
5. On success, a confirmation or gallery is shown.

---

## 🚀 Setup Instructions

### Prerequisites

- Node.js & npm
- GitHub account
- Cloudinary account

---
### 1. Install Dependencies

npm install


## 2. Set Up Cloudinary
Create a free account on Cloudinary, then get these details:

           cloud_name
           api_key
           api_secret


 
### 3.  Create a .env file and add: 
           CLOUD_NAME=your_cloud_name
           API_KEY=your_api_key
           API_SECRET=your_api_secret
 ### 4. Start the Server
           node index.js
           Visit http://localhost:3000 in your browser

 
###  📂 Folder Structure

cloud-storage-FIV/
│
├── public/              # Static files (CSS, JS)
├── uploads/             # Temporary local storage (if used)
├── views/               # HTML or EJS templates
├── .env                 # Environment variables
├── index.js             # Main server file
└── package.json         # Project metadata


### 📸 Sample UI

![WhatsApp Image 2025-06-14 at 21 42 01_64a304b5](https://github.com/user-attachments/assets/1de2f990-c6ee-495d-b84e-b0bf07acc655)

 

![WhatsApp Image 2025-06-14 at 21 51 56_2eff50c7](https://github.com/user-attachments/assets/9203e12f-73b6-42c4-a03f-435218b292a0)



![WhatsApp Image 2025-06-14 at 21 52 15_1a1adc9b](https://github.com/user-attachments/assets/4504bc61-0b04-4281-82c7-bfaffac1db3f)

 ---

## 🙋‍♂️ About Me

Hi, I'm **Mangesh Kanaujiya**, a passionate Full-Stack Web Developer and Cloud Enthusiast.  
I enjoy building responsive web apps and exploring cloud services like AWS and Cloudinary.

### 📚 Skills:
- 💻 Web: HTML, CSS, JavaScript, Node.js, Express.js
- 💻 I am study AWS could and Networking
- 🌐 APIs & Cloud: REST APIs, Cloudinary, AWS (Basics)
- 🛠 Tools: Git, GitHub, VS Code, Postman
- 📁 Database (Optional): MongoDB / MySQL

  ### 📫 Connect With Me:
- GitHub: [@mangeshkanaujiya]( https://github.com/mangeshkanaujiya)
- LinkedIn: [linkedin.com/in/mangesh-kanaujiya]( https://www.linkedin.com/in/mangesh-kanaujiya-0438bb2a5 )
