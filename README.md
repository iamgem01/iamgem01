from pathlib import Path

readme = r'''<div align="center">

# Hi, I'm Gemma 👋

### Software Engineering Student

<p>
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&center=true&vCenter=true&width=520&lines=Hi+guys%2C+I'm+Gemma!;Bonjour+%C3%A0+tous%2C+je+suis+Gemme!;I'm+studying+Software+Engineering;Building+and+learning+every+day." alt="Typing SVG" />
</p>

<p>
  <a href="https://github.com/iamgem01">GitHub</a>
  &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/tran-bich-ngoc-224b26245/">LinkedIn</a>
  &nbsp;·&nbsp;
  <a href="https://discord.com/channels/@gemisme">Discord</a>
</p>

</div>

---

## About Me

I'm a **Software Engineering student** at the **Da Nang University of Science and Technology, Viet Nam**.

I'm interested in building software that is simple, useful, and well-structured.  
Currently exploring web development, backend systems, databases, and AI-powered applications.

---

## Languages & Technologies

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,java,c,cpp,cs,html,css,js,react,mysql,mongodb,git,gitlab,figma" />
</p>

---

## What I'm Learning

- Software architecture & backend development
- Modern web development
- Database design and management
- AI integration in software applications
- Writing cleaner and more maintainable code

---

## A Little About My Work

I enjoy working across different parts of the software development process:

**Design** → **Develop** → **Test** → **Improve**

From UI/UX and database design to application development, I like understanding how the pieces fit together rather than focusing on just one layer.

---

<div align="center">

### Thanks for visiting my profile ♡

*Learn. Build. Improve.*

</div>
'''

path = Path("/mnt/data/README.md")
path.write_text(readme, encoding="utf-8")
print(f"Updated: {path}")
