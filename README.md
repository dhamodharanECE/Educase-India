# **Company         : Educase India - Assignment**
Tech Stack      : Frontend Project 
Technologies    : React Js, HTML5, CSS
Building Blocks : Home Pade, Register Page, Login Page, User Page

🚀 Features:

✅ User Registration with input validation

✅ Login Authentication using localStorage

✅ Dashboard Display with dynamic user data

✅ Email and Phone Validation using Regular Expressions

✅ Persistent Data Storage via localStorage

✅ Responsive Design using CSS

✅ Font Awesome Camera Icon for profile avatar

🛠️ Tech Stack:
Technology	        => Description
React.js	        => Frontend framework for UI
JavaScript (ES6+)	=> Application logic and validation
CSS3	            => Styling and layout
Font Awesome	    => Icons for profile section
LocalStorage API	=> To store and retrieve user data

📂 Folder Structure:
PopX-Account-App/
│
├── src/
│   ├── components/
│   │   ├── Register.js
│   │   ├── Login.js
│   │   └── Dashboard.js
│   │
│   ├── assets/
│   │   └── downloads.png
│   │
│   ├── App.js
│   ├── App.css
│   ├── index.js
│   └── styles/
│       ├── Register.css
│       ├── Login.css
│       └── Dashboard.css
│
├── public/
│   └── index.html
│
├── package.json
└── README.md

🧩 Component Overview:
🟣 Register.js

Captures user details: Full Name, Email, Phone, Password, Company Name.

Validates email and phone number before submission.

Stores the form data in localStorage.

On success, navigates to the Login page.

🟣 Login.js

Takes Email and Password as input.

Validates credentials against stored data in localStorage.

If credentials match → Redirects to Dashboard.

🟣 Dashboard.js

Fetches and displays registered user’s Name and Email.

Displays a profile image (with a camera icon for future photo uploads).

Shows a short account description.

🧠 Logic Flow:

📝 Register → Save data in localStorage

🔐 Login → Check credentials from localStorage

🧑‍💼 Dashboard → Display saved user data dynamically

⚙️ Setup Instructions:
1️⃣ Clone the repository
git clone https://github.com/yourusername/PopX-Account-App.git
cd PopX-Account-App

2️⃣ Install dependencies
npm install

3️⃣ Run the app
npm start


App will start on 👉 http://localhost:3000

💾 LocalStorage Example:

Here’s how user data is stored in the browser’s localStorage:

{
  "username": "Dhamodharan S",
  "phonenumber": "9876543210",
  "email": "dhamo@gmail.com",
  "password": "12345",
  "companyname": "PopX"
}

🎨 Font Awesome Setup:

Add this line inside your public/index.html <head> tag for camera icons to work:

<link
  rel="stylesheet"
  href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css"
/>

📸 Example Preview:
Register Page

Users can create an account by filling in the required details.

Login Page:

Validates credentials before granting access.

Dashboard:

Displays user profile with name, email, and avatar.

🔒 Validation Rules:
Field	Validation
Email	Must follow standard email format
Phone Number	Must be exactly 10 digits
Password	Required field
Name	Required field
🧑 Author

👤 Dhamodharan S
Full Stack Web Developer Intern
📧 dhamodharansece23@gmail.com
]
💼 https://github.com/dhamodharanECE

📜 License:

This project is licensed under the MIT License.
You are free to use and modify it for educational or personal projects.
