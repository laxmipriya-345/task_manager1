# 📋 TaskFlow - Task Manager UI

A modern, responsive Task Manager application with beautiful UI components and smooth animations. Built with pure HTML, CSS, and JavaScript.

## ✨ Features

### 🔐 Authentication
- **Login Page** - Secure user authentication with validation
- **Signup Page** - New user registration with password confirmation
- **Demo Credentials** - Pre-filled demo account for quick testing

### 📊 Dashboard
- **Statistics Cards** - Visual overview of tasks (Total, Completed, In Progress, Overdue)
- **Quick Actions** - One-click access to common tasks
- **Progress Tracking** - Visual progress bar for daily tasks
- **Recent Tasks** - List of recent tasks with priority levels
- **Notifications** - Real-time notification system

### 📝 Task Management
- **Create Tasks** - Modal form with title, description, priority, and due date
- **Complete Tasks** - Checkbox to mark tasks as complete
- **Delete Tasks** - Animated deletion with confirmation
- **Priority Labels** - High, Medium, Low with color coding
- **Task Tags** - Categorize tasks with custom tags

### 🎨 UI/UX
- **Responsive Design** - Works on all devices (desktop, tablet, mobile)
- **Smooth Animations** - Transitions, hover effects, and micro-interactions
- **Modern Design** - Clean, minimal, and professional
- **Interactive Elements** - Hover effects, click feedback, and visual cues
- **Toast Notifications** - User feedback for all actions

## 📸 Screenshots

### 🔐 Login Page
![Login Page](screenshots/login-page.png)
*Clean and modern login interface with validation*

### 📊 Dashboard Overview
![Dashboard](screenshots/dashboard.png)
*Complete dashboard with statistics, quick actions, and task management*

### 📝 Task Creation Modal
![Task Creation](screenshots/task-creation.png)
*Intuitive task creation form with priority and due date selection*

## 🚀 Live Demo

Visit the live demo: [TaskFlow Demo](https://YOUR_USERNAME.github.io/task-manager-ui)

**Demo Credentials:**
- Email: `demo@dreamtravel.com`
- Password: `password123`

## 🛠️ Technologies

- **HTML5** - Semantic markup
- **CSS3** - Flexbox, Grid, Animations, Transitions
- **JavaScript** - Vanilla JS, ES6+
- **LocalStorage** - Client-side data persistence

- task-manager-ui/
│
├── index.html # Login Page
├── signup.html # Signup Page
├── dashboard.html # Main Dashboard
├── task-form.html # Task Creation Form
│
├── styles/
│ ├── style.css # Global styles
│ ├── login.css # Login/Signup styles
│ ├── dashboard.css # Dashboard styles
│ └── task-form.css # Form styles
│
├── screenshots/ # Application screenshots
│ ├── login-page.png
│ └── dashboard.png
│
├── README.md # Documentation
└── .gitignore # Git ignore file

text

## 🔧 Installation

### Clone the Repository
```bash
git clone https://github.com/YOUR_USERNAME/task-manager-ui.git
cd task-manager-ui
Open in Browser
Simply open index.html in your preferred browser.

Local Development
bash
# Using Python
python -m http.server 8000

# Using VS Code Live Server
# Right-click on index.html → Open with Live Server
📱 Responsive Design
Device	Breakpoint	Layout
Desktop	> 1024px	Full sidebar, multiple columns
Tablet	768px - 1024px	Collapsible sidebar, 2-column grid
Mobile	< 768px	Hamburger menu, single column
🎯 Features in Detail
Authentication Flow
User signs up with name, email, and password

Data stored in localStorage

User logs in with registered credentials

Redirected to dashboard

Task Management
Create task with title, description, priority, and due date

View tasks in dashboard with priority colors

Mark tasks as complete with checkbox

Delete tasks with smooth animation

Search and filter tasks

Dashboard Features
Statistics: Real-time task counts

Progress: Visual representation of task completion

Recent Tasks: Quick view of latest tasks

Notifications: Alert system for task updates

🎨 Color Palette
Color	Hex Code	Usage
Primary	#667eea	Buttons, links, highlights
Secondary	#764ba2	Gradients, accents
Success	#10b981	Completed tasks, positive stats
Warning	#f59e0b	Medium priority, warnings
Danger	#ef4444	High priority, overdue tasks
Dark	#1a1a2e	Text, sidebar background
💡 Usage Guide
Login
Open index.html

Use demo credentials or sign up

Click "Login" to access dashboard

Create Task
Click "+ New Task" button

Fill in task details

Click "Create Task"

Task appears in recent tasks list

Manage Tasks
✅ Click checkbox to complete

🗑️ Click X to delete

📌 Priority colors indicate urgency

Responsive Navigation
Click ☰ (hamburger) on mobile

Sidebar slides in/out smoothly

🤝 Contributing
Contributions are welcome! Please follow these steps:

Fork the repository

Create a feature branch

bash
git checkout -b feature/amazing-feature
Commit your changes

bash
git commit -m 'Add amazing feature'
Push to branch

bash
git push origin feature/amazing-feature
Open a Pull Request

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

🙏 Acknowledgments
Icons from Unicode Emoji

Design inspiration from modern UI trends

Background gradients from uiGradients

📞 Contact
Laxmipriya Rout
routlaxmipriya121@gmail.com

Project Link: https://github.com/YOUR_USERNAME/task-manager-ui

🌟 Show Your Support
Give a ⭐️ if this project helped you!

🔮 Future Enhancements
Backend integration with Node.js/Express

Database connection (MongoDB/PostgreSQL)

User authentication with JWT

Drag-and-drop task reordering

Task categories and filters

Calendar view for tasks

Team collaboration features

File attachments for tasks

Email notifications

Dark mode toggle

Export/Import tasks

Mobile app (React Native)

🐛 Known Issues
None currently - please report any issues!

## 📂 Project Structure
