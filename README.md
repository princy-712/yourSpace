# Your Space
> _Write it. Feel it. Keep it._  
> _Pieces of your day, saved your way._

**Your Space** is a beautifully designed full-stack digital journaling platform. Whether you're expressing your thoughts, reflecting on your day, or simply writing to clear your mind — Your Space offers a calm, secure, and minimalistic experience built with modern technologies.

## 🌟 Features

### 👤 User Management
- Register with name, username, age, and password
- Secure login with hashed passwords
- JWT-based session authentication via HTTP cookies
- Password recovery using DOB (Date of Birth)

### 🧠 Digital Journaling System
- Create, edit, and delete journal entries
- Like (❤️) posts to mark favorites
- Responsive and animated interface
- Posts displayed in reverse chronological order

### 🖼️ Profile Customization
- Upload and display a profile picture
- Profile picture stored securely and shown on dashboard

### 🔒 Secure Access
- Protected routes with custom middleware
- Unauthorized users are redirected to login

### 💅 Beautiful, Responsive UI
- Built with Tailwind CSS and Glassmorphism style
- Smooth animations and transitions
- Fully responsive design for mobile, tablet, and desktop

---



## 🧑‍💻 Tech Stack

**Backend**: Node.js, Express.js
- **Frontend**: EJS Templates, Tailwind CSS
- **Database**: MongoDB (via Mongoose)
- **Authentication**: JWT (JSON Web Token)
- **Password Security**: Bcrypt
- **File Uploads**: Multer
- **Icons**: Font Awesome

---

## Project Structure

your-space/

├── ```config/```

│ └── ```multerconfig.js```

├── ```models/```

│ ├── ```user.js```

│ └── ```post.js```

├── ```public/```

│ └── ```images/uploads/```

├── ```views/```

│ ├── ```profile.ejs```

│ ├── ```login.ejs```

│ ├── ```index.ejs```

│ ├── ```forgetpwd.ejs```

│ └── ```overview.ejs```

├── ```app.js```

├── ```package.json```

└── ```README.md```


## 🚀 Setup & Run Locally

1. **Clone the repository**
<```
git clone https://github.com/your-username/your-space.git
cd your-space```>

2. **Install dependencies**
<```
npm install```

3. **Start MongoDB**
<```
Make sure MongoDB is running on your system (default mongodb://localhost:27017/yourspace).```

4. **Run the app**
<```
Copy code
node app.js```

5. **Visit in Browser**

arduino
Copy code
http://localhost:3000

## 💡 Future Enhancements

**#Add user themes (light/dark mode)**

**#Export journal entries as PDF**

**#Enable comments or reactions on posts**

**#Add calendar view for past entries**

**#Add mood tracking (emoji-based)**
<img width="650" height="692" alt="Screenshot 2026-03-30 at 11 49 51 AM" src="https://github.com/user-attachments/assets/cbe4b4ea-9a07-443c-a6f1-bd23afb79342" />


<img width="872" height="739" alt="Screenshot 2026-03-30 at 11 50 28 AM" src="https://github.com/user-attachments/assets/37074790-504b-4ba6-b7e7-2e7232ad0364" />



<img width="1447" height="837" alt="Screenshot 2026-03-30 at 3 34 23 PM" src="https://github.com/user-attachments/assets/31260f4d-a9d4-4b07-a390-d90a097fcff6" />








