## 🚀 Smart Task Scheduler

🔗 **Live Application:** https://planifytasks.netlify.app/

## 📌 Project Overview

**Smart Task Scheduler** is a web-based productivity application designed to help users efficiently manage their daily tasks through intelligent scheduling and reminder systems.

Unlike traditional to-do list applications, this project emphasizes **task completion, consistency, and productivity tracking** rather than just task creation. It integrates time-based reminders, recurring task management, and performance analytics to support effective daily planning.

## 🎯 Objectives

* Design a system that enhances daily productivity and consistency
* Implement time-based and event-based task reminders
* Provide an intuitive and user-friendly interface
* Track and visualize weekly performance
* Efficiently manage repeating and missed tasks

## 📸 Application Screenshots

## home-dashboard.png
![image_alt](https://github.com/sakshiparadkar/planify-app/blob/9017fd8e3db3b4d8283f52623cf5ffd19e513e65/imgs/Screenshot%20(392).png)
## calendar-view.png
![image_alt](https://github.com/sakshiparadkar/planify-app/blob/9017fd8e3db3b4d8283f52623cf5ffd19e513e65/imgs/Screenshot%20(393).png)
## settings.png
![image_alt](https://github.com/sakshiparadkar/planify-app/blob/9017fd8e3db3b4d8283f52623cf5ffd19e513e65/imgs/Screenshot%20(394).png)
## weekly-progress-and-task-reminder-notification.png
![image_alt](https://github.com/sakshiparadkar/planify-app/blob/9017fd8e3db3b4d8283f52623cf5ffd19e513e65/imgs/Screenshot%20(396).png)
## add-task.png
![image_alt](https://github.com/sakshiparadkar/planify-app/blob/9017fd8e3db3b4d8283f52623cf5ffd19e513e65/imgs/Screenshot%20(398).png)
## completed-remaining-tasks.png
![image_alt](https://github.com/sakshiparadkar/planify-app/blob/9017fd8e3db3b4d8283f52623cf5ffd19e513e65/imgs/Screenshot%20(399).png)


## ✨ Key Features

### 📋 Task Management

* Create, update, and delete tasks
* Add notes for better context
* Mark tasks as completed

### ⏰ Scheduling System

* Assign specific date and time to tasks
* Supports 12-hour (AM/PM) format

### 🔔 Notification System

* Multiple reminder options:

  * At scheduled time
  * 10 minutes before
  * 1 hour before
  * 1 day before
* Built using Browser Notifications API

### 🔁 Repeating Tasks

* Daily and weekly repetition
* Tracks completion for each occurrence

### 📊 Productivity Tracking

* Weekly completion percentage
* Progress bar visualization
* Day-wise performance tracking

### 📅 Dual Interface

* **List View** → Task-focused
* **Calendar View** → Date-focused

### 🎯 Priority Management

* Categorization into High, Medium, and Low priority

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3, JavaScript
* **Storage:** LocalStorage API
* **Notifications:** Browser Notifications API


## ⚙️ System Workflow

1. User creates a task with date, time, and priority
2. Task is stored using LocalStorage
3. Reminder timers are scheduled via JavaScript
4. Notifications are triggered at defined intervals
5. Completion status is tracked and reflected in weekly analytics


## 📂 Project Structure

```
Smart-Task-Scheduler/
│
├── index.html   # Main application (UI + Logic)
└── README.md    # Documentation
```

---

## 🚀 How to Run the Project

```bash
# Clone the repository
git clone https://github.com/sakshiparadkar/planify-app.git

# Navigate to project folder
cd planify-app
```

* Open `index.html` in any web browser


## 🔔 Notification Setup

1. Click **Enable Notifications** in the application
2. Allow browser notification permissions
3. Keep the browser tab active to receive alerts


## 💡 Key Learnings

* Implementation of JavaScript-based scheduling logic
* Handling date and time operations effectively
* Designing user-centric UI/UX
* Utilizing LocalStorage for persistent data
* Integrating browser notification systems


## 🔮 Future Enhancements

* User authentication system
* Cloud database integration (Firebase / MongoDB)
* Mobile application using React Native
* Drag-and-drop task management
* Dark/Light mode support


## 📄 License

This project is licensed under the MIT License.


## 👩‍💻 Author

**Sakshi Paradkar**
Computer Science Student
