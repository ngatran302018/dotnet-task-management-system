<div align="center">

# 🌐 TaskSphere

### *Optimizing Task Lifecycles via Relational Frameworks*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![.NET Framework](https://img.shields.io/badge/.NET-Framework-512BD4?logo=.net)](https://dotnet.microsoft.com/)
[![C#](https://img.shields.io/badge/C%23-239120?logo=c-sharp&logoColor=white)](https://docs.microsoft.com/en-us/dotnet/csharp/)
[![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?logo=microsoft-sql-server&logoColor=white)](https://www.microsoft.com/en-us/sql-server)

**Your comprehensive solution for efficient task and project management**

[Features](#-features) • [Installation](#-installation) • [Usage](#-usage) • [Contributing](#-contributing)

---

</div>

## 📋 Overview

**TaskSphere** is a powerful, intuitive task management application built with C# and the .NET framework. Designed for productivity enthusiasts and professionals alike, TaskSphere transforms the way you organize, track, and complete your tasks with a sleek graphical interface and robust database integration.

Whether you're managing personal to-dos or coordinating complex project workflows, TaskSphere provides the tools you need to stay organized and efficient.

---

## ✨ Features

<table>
<tr>
<td width="50%">

### 📝 Task Management
- ✅ Create and organize tasks effortlessly
- 📊 Build comprehensive to-do lists
- 🎯 Track task progress in real-time

</td>
<td width="50%">

### 🎨 Smart Organization
- 🔄 Set task statuses (Pending/Completed)
- ⭐ Mark important tasks for priority access
- 🗑️ Quick task deletion functionality

</td>
</tr>
<tr>
<td width="50%">

### 📊 Dashboard Overview
- 📈 Visual task analytics
- 🔍 Quick status overview
- 💡 Important task highlights

</td>
<td width="50%">

### 🔐 User Management
- 👤 Secure login/signup system
- 💾 Persistent data storage
- 🔒 User-specific task isolation

</td>
</tr>
</table>

---

## 🖼️ Application Preview

<div align="center">

### 🔑 Login Interface
<img src="sc/Login.png" alt="Login Page" width="700"/>

### 📊 Main Dashboard
<img src="sc/Dashboard.png" alt="Dashboard Page" width="700"/>

### 📁 Project Management
<img src="sc/AllProjects.png" alt="All Projects Page" width="700"/>

</div>

---

## 🛠️ Technology Stack

<div align="center">

| Technology | Purpose |
|------------|---------|
| **C#** | Core programming language |
| **.NET Framework** | Application framework |
| **Windows Forms** | GUI development |
| **SQL Server** | Database management |
| **GUNA.UI2** | Modern UI components |

</div>

---

## 🚀 Getting Started

### 📋 Prerequisites

Before you begin, ensure you have the following installed:

- 🖥️ **Windows OS** (Windows 10 or later recommended)
- 💻 **Visual Studio** (2019 or later)
- 🗄️ **SQL Server** (Express edition or higher)
- 📦 **.NET Framework** (4.7.2 or later)

### 📥 Installation

Follow these steps to get TaskSphere up and running:

#### 1️⃣ Clone the Repository

```bash
git clone https://github.com/burhanahmed1/Task-Management-System.git
cd Task-Management-System
```

#### 2️⃣ Open in Visual Studio

- Launch **Visual Studio**
- Open `TaskSphere.sln` solution file
- Wait for NuGet packages to restore automatically

#### 3️⃣ Configure the Database

- 📂 Navigate to the `Database` folder
- 🔄 Restore the database backup file
- ⚙️ Update the connection string in `App.config`:

```xml
<connectionStrings>
    <add name="TaskSphereDB" 
         connectionString="Server=YOUR_SERVER;Database=TaskSphere;Integrated Security=true;" 
         providerName="System.Data.SqlClient" />
</connectionStrings>
```

#### 4️⃣ Build and Run

- 🔨 Build the solution (`Ctrl + Shift + B`)
- ▶️ Run the application (`F5`)
- 🎉 Start managing your tasks!

---

## 💡 Usage Guide

### 🆕 First Time Users

1. **📝 Sign Up**
   - Launch TaskSphere
   - Click "Sign Up" on the login screen
   - Fill in your details
   - Your account is now created and stored securely!

2. **🔑 Subsequent Logins**
   - Simply enter your credentials
   - Access your personalized task dashboard

### 🎯 Core Workflows

<details>
<summary><b>📌 Creating Tasks</b></summary>

- Navigate to the task creation panel
- Enter task title and description
- Set priority and deadline (optional)
- Click "Save" to add to your list

</details>

<details>
<summary><b>📋 Managing To-Do Lists</b></summary>

- Create custom lists for different projects
- Drag and drop tasks between lists
- Organize tasks by category or priority
- Archive completed lists

</details>

<details>
<summary><b>✅ Updating Task Status</b></summary>

- Click on any task to view details
- Toggle status between "Pending" and "Completed"
- Track your progress in real-time

</details>

<details>
<summary><b>⭐ Prioritizing Tasks</b></summary>

- Click the star icon on important tasks
- View all starred tasks in the "Important" filter
- Never miss critical deadlines

</details>

<details>
<summary><b>🗑️ Deleting Tasks</b></summary>

- Select the task you want to remove
- Click the delete icon
- Confirm deletion when prompted

</details>

<details>
<summary><b>📊 Dashboard Analytics</b></summary>

- View task completion statistics
- Monitor upcoming deadlines
- Track productivity trends
- Filter by status, priority, or date

</details>

### 🚪 Exiting the Application

- Click the **Exit** icon in the bottom-left panel
- Your data is automatically saved

---

## 🤝 Contributing

We welcome contributions from the community! Here's how you can help:

### 🌟 Ways to Contribute

- 🐛 Report bugs and issues
- 💡 Suggest new features
- 📝 Improve documentation
- 🔧 Submit pull requests

### 📝 Contribution Process

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/AmazingFeature`)
3. **Commit** your changes (`git commit -m 'Add some AmazingFeature'`)
4. **Push** to the branch (`git push origin feature/AmazingFeature`)
5. **Open** a Pull Request

---

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

```
MIT License - Free to use, modify, and distribute
```

<h3 align="center">Connect with me:</h3>
<p align="center">
  <a href="https://instagram.com/_mr_2001__" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="_mr_2001__" height="30" width="40" /></a>
  <a href="https://linkedin.com/in/www.linkedin.com/in/pavith-bambaravanage-465300293" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="pavith-bambaravanage-465300293" height="25" width="35" /></a>
  <a href="https://www.hackerrank.com/@pavith_db" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/hackerrank.svg" alt="@pavith_db" height="40" width="45" /></a>
  <a href="https://www.leetcode.com/pavith_db" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/leet-code.svg" alt="pavith_db" height="30" width="40" /></a>
  <a href="mailto:pavithd2020@gmail.com" target="blank"><img align="center" src="https://github.com/TheDudeThatCode/TheDudeThatCode/raw/master/Assets/Gmail.svg" alt="pavithd2020@gmail.com" height="30" width="40" /></a>
</p>

