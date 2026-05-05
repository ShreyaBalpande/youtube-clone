# 📺 YouTube Clone (Frontend)

A responsive **YouTube homepage clone** built using HTML and CSS, designed to replicate the look and feel of the original platform. This project focuses on **UI design, layout structuring, and responsive styling**.

🌐 **Live Demo:**  
https://shreyabalpande.github.io/youtube-clone/

---

## 🚀 Features

- 🎯 Clean and modern YouTube-inspired UI  
- 📱 Responsive design for multiple screen sizes  
- 🔍 Header with search bar layout  
- 📺 Video grid (recommended section)  
- 📂 Sidebar navigation styling  
- ⚡ Built using Flexbox and CSS layout techniques  

---

## 🛠️ Tech Stack

- **HTML5** – Structure of the webpage  
- **CSS3** – Styling and layout  
- **Flexbox / Grid** – Responsive design  

---

## 🌍 Deployment

This project is deployed using **GitHub Pages** and is accessible globally.

---

## ⚙️ DevOps & Automation

This project includes a **CI/CD pipeline** to automate deployment.

### 🔧 What I Implemented

- Deployed using **GitHub Pages**
- Set up **CI/CD pipeline using GitHub Actions**
- Automatic deployment on every push to `main`
- Version control using Git
- Secure workflow using built-in GitHub tokens

### 🔄 Workflow
Code → GitHub → GitHub Actions → Auto Deploy → Live Website 🌍

---

## 🚧 Challenges Faced

During development and deployment, I encountered and solved several real-world issues:

- ❌ **Push rejected (fetch first error)**  
  → Resolved using `git pull --rebase` to sync branches

- 🔐 **GitHub Push Protection (secret detected)**  
  → Accidentally exposed a token in workflow  
  → Fixed by removing it and using `${{ secrets.GITHUB_TOKEN }}`

- ⚠️ **Invalid workflow file (YAML errors)**  
  → Faced duplicate `on` and `jobs` issues  
  → Learned correct GitHub Actions structure

- 🚫 **Deployment failure (exit code 128)**  
  → Resolved by switching to official GitHub Pages deployment method

- 🔄 **Branch synchronization issues**  
  → Learned how to manage local vs remote repositories properly

---

## 🎯 Learning Outcomes

- Building real-world UI layouts  
- Understanding CSS layout systems  
- Implementing CI/CD pipelines  
- Debugging Git and GitHub issues  
- Handling deployment automation  
- Managing secure workflows 

---

## 🚧 Future Improvements

- Add JavaScript for interactivity  
- Improve mobile responsiveness  
- Add testing step in CI/CD pipeline  
- Dockerize the application  
- Explore cloud deployment using AWS  
---

## 📌 Disclaimer

This project is created for **educational purposes only** and is not affiliated with YouTube.

---

## 🙏 Credits

This project was inspired by and built with guidance from the tutorials by **SuperSimpleDev**.  
Their explanations made it easy to understand and apply core frontend concepts effectively.

- YouTube: https://www.youtube.com/@SuperSimpleDev

---

## 🙌 Acknowledgements

Inspired by the design and layout of YouTube.

---

## 📬 Connect With Me

- GitHub: https://github.com/ShreyaBalpande  
- Special thanks to **SuperSimpleDev** for clear and beginner-friendly tutorials that helped in building this project
---

## 🔄 Future Updates

I plan to continue improving this project by implementing **deployment enhancements and DevOps practices**, including automating the deployment process (CI/CD).  
Any future changes and improvements will be regularly updated in this repository.

---

⭐ If you like this project, consider giving it a star!
