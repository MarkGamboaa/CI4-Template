# 🚀 CI4-Template Setup Guide

This guide will walk you through setting up the **CodeIgniter 4 Template** inside your XAMPP `htdocs` directory.

---

## 📦 Step 1: Go to XAMPP htdocs directory

Open **CMD** and run:

```cmd
cd C:\xampp\htdocs
```

---

## 📥 Step 2: Clone the Repository

This will create a new folder called `CI4-Template`.

```cmd
git clone https://github.com/MarkGamboaa/CI4-Template.git
```

---

## ✏ Step 3: Rename the Folder

Change the folder name CI4-Template to your own project name (replace YourProjectName):

```cmd
ren CI4-Template YourProjectName
```

➡ Example:  
ren CI4-Template CI4-App

---

## 📂 Step 4: Move Into Your Project Folder

Navigate into your newly renamed folder:

```cmd
cd C:\xampp\htdocs\YourProjectName
```

➡ Example:  
cd C:\xampp\htdocs\CI4-App

---

## 💻 Step 5: Open in VS Code

Open the project in VS Code:

```cmd
code .
```

## One line command

Just replace YourProjectName with whatever you want to name your project.

```cmd
cd C:\xampp\htdocs && git clone https://github.com/MarkGamboaa/CI4-Template.git && ren CI4-Template YourProjectName && cd YourProjectName && code .
```
Dont forget to edit $baseURL

```cmd
public string $baseURL = 'http://localhost/CI4-Template/';
```
