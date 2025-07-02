---
layout: default
---

<h1 style="margin-top: 2rem;">👋 Hi, I’m Sakshi</h1>

## About Me

I hold a **Master’s degree in Software Engineering for Industrial Applications** from **Hof University of Applied Sciences, Germany**, with strong academic exposure to:

- ✅ Project management  
- ✅ Component-oriented software development  
- ✅ Industry 4.0 systems  

I enjoy solving problems with **structured, maintainable code** and am currently focused on **DevOps** and **AI**.

---

## ⚙️ Tech Stack

### Languages & Frameworks  
<div align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white" />
</div>

### Tools & Platforms  
<div align="left">
  <img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/VS%20Code-007ACC?style=flat&logo=visual-studio-code&logoColor=white" />
  <img src="https://img.shields.io/badge/Jira-0052CC?style=flat&logo=jira&logoColor=white" />
</div>
<br>

---
## 🚀 Current Focus

✨ Building projects with Python & automation  
📚 Upskilling in **DevOps** and **AI** for intelligent automation & cloud deployment  
🤝 Open to collaborations and learning opportunities

---
## 📂 Projects

<table>
  <thead>
    <tr><th>Name</th><th>Description</th><th>Tech Stack</th></tr>
  </thead>
  <tbody>
    {% for project in site.data.projects %}
    <tr>
      <td>{{ project.name }}</td>
      <td>{{ project.description }}</td>
      <td>{{ project.tech }}</td>
    </tr>
    {% endfor %}
  </tbody>
</table>
➡️ *More coming soon!*

---
## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=sjain2580&show_icons=true&theme=default&hide_title=true" width="60%" />
</p>

---
## 📫 Let’s Connect

<div align="left">
<a href="https://www.linkedin.com/in/sjain04/" target="_blank" rel="noopener noreferrer">
  <img src="https://img.shields.io/badge/LinkedIn-blue?logo=linkedin&logoColor=white&style=for-the-badge" alt="LinkedIn Badge"/>
</a>
&nbsp;&nbsp;
<a href="mailto:sjain040395@gmail.com">
  <img src="https://img.shields.io/badge/Email-blue?style=for-the-badge&logo=gmail&logoColor=white" alt="Email Badge"/>
</a>

</div>
## ✉️ Contact Me

<div align="center">
  <button onclick="toggleForm()" style="background-color:#0A66C2;color:white;padding:10px 20px;border:none;border-radius:5px;cursor:pointer;">
    Get in Touch
  </button>
</div>

<div id="contact-form" style="display:none; margin-top:20px; max-width: 500px; margin:auto;">
  <form action="https://formspree.io/f/your-form-id" method="POST">
    <label>Name</label><br>
    <input type="text" name="name" required style="width:100%; padding:8px; margin-bottom:10px;" /><br>
    
    <label>Email</label><br>
    <input type="email" name="email" required style="width:100%; padding:8px; margin-bottom:10px;" /><br>
    
    <label>Message</label><br>
    <textarea name="message" rows="5" required style="width:100%; padding:8px;"></textarea><br><br>
    
    <button type="submit" style="background-color:#0A66C2;color:white;padding:10px 20px;border:none;cursor:pointer;">Send</button>
  </form>
</div>

<script>
  function toggleForm() {
    var form = document.getElementById("contact-form");
    form.style.display = form.style.display === "none" ? "block" : "none";
  }
</script>
🙏 Thanks for stopping by! 😊
