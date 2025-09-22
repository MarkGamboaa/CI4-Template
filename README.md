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

```cmd
git clone https://github.com/MarkGamboaa/CI4-Template.git
```

This will create a new folder called `CI4-Template`.

---

## ✏ Step 3: Rename the Folder

Change `CI4-Template` to your preferred project folder name:

```cmd
ren CI4-Template <newFolderName>
```

➡ Example:  
```cmd
ren CI4-Template CI4-App
```

---

## 📂 Step 4: Move Into Your Project Folder

```cmd
cd C:\xampp\htdocs\<newFolderName>
```

➡ Example:  
```cmd
cd C:\xampp\htdocs\CI4-App
```

---

## 💻 Step 5: Open in VS Code

```cmd
code .
```

This will launch your project in Visual Studio Code.

---

## 🎯 Next Steps

- Copy `.env.example` to `.env` and configure your database + baseURL.  
- Make sure the `writable/` directory has proper permissions.  
- Start Apache + MySQL from XAMPP and you’re ready to go.  
- Visit your project at [http://localhost/<newFolderName>/public](http://localhost/<newFolderName>/public)

---

## 📄 License

MIT License — feel free to use and modify.
