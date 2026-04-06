# 🌐 AJAX REST API Projects

This repository contains two simple web applications built using **HTML, JavaScript (AJAX)** and **REST APIs**.

---

## 📌 Projects Included

### 1️⃣ GitHub Repository Viewer

* Enter a GitHub username
* Fetches all public repositories using REST API
* Displays results in an HTML table

### 2️⃣ University Finder

* Enter a country name
* Fetches universities using REST API
* Displays results in a dropdown list

---

## 🚀 Technologies Used

* HTML5
* JavaScript (AJAX - XMLHttpRequest)
* REST APIs

---

## 🔗 APIs Used

* GitHub API
  https://api.github.com/users/{username}/repos

* Universities API
  http://universities.hipolabs.com/search?country={country}

---

## 📂 Project Structure

```
project-folder/
│
├── index.html          
└── university.html     
```

---

## ⚙️ How to Run

### Step 1: Clone the repository

```
git clone https://github.com/your-username/your-repo-name.git
```

### Step 2: Navigate into folder

```
cd your-repo-name
```

### Step 3: Open files in browser

```
start index.html
start university.html
```

---

## 🧪 Example Usage

### GitHub Viewer

Input:

```
octocat
```

Output:

* List of repositories with clickable links

### University Finder

Input:

```
India
```

Output:

* List of universities in India

---

## ⚠️ Notes

* Requires internet connection
* APIs may have rate limits
* For best results, use Chrome or run using Live Server

---

## 📌 Future Improvements

* Use Fetch API instead of XMLHttpRequest
* Add error handling
* Improve UI with Bootstrap
* Combine both projects into a single page

---

## 👨‍💻 Author

Your Name

---

## 📄 License

This project is for educational purposes.
