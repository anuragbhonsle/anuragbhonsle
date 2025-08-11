<!-- HEADER: Animated typing effect -->
<h1 align="center">
  Hey, I’m <a href="https://github.com/your_github_username" target="_blank">Anurag</a>! 👋
</h1>
<p align="center">
  <em>
    <strong>
      <span id="typed-text"></span>
    </strong>
  </em>
</p>

<!-- PROFILE STATS -->
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=your_github_username&show_icons=true&theme=radical" alt="Anurag's GitHub stats" />
</p>

---

### 🚀 About Me
- 🔥 React Developer & UI Wizard  
- 💻 Daily LeetCode hustler (232-day streak!)  
- 🧠 DSA lover & problem-solving addict  
- 🛠️ Backend newbie: Node.js, Express, MongoDB  
- ☕ Fueled by coffee & good vibes  

---

### 🛠 Skills

<p align="center">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" />
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" />
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
</p>

---

### 💼 Projects

| Project                                | Description                                  | Link                                      |
|--------------------------------------|----------------------------------------------|-------------------------------------------|
| [LeetScape](https://github.com/your_github_username/LeetScape)   | React frontend for LeetCode users             | [Repo](https://github.com/your_github_username/LeetScape) |
| [Animeverse](https://github.com/your_github_username/Animeverse) | Manage & track anime watchlists               | [Repo](https://github.com/your_github_username/Animeverse) |
| [Eclipz](https://github.com/your_github_username/Eclipz)         | Unique React project with modern UI           | [Repo](https://github.com/your_github_username/Eclipz)     |

---

### 📫 Connect with me

<p align="center">
  <a href="https://linkedin.com/in/your_linkedin" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://twitter.com/your_twitter" target="_blank">
    <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" />
  </a>
  <a href="mailto:your_email" target="_blank">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

---

### 🎯 Quote of the Day

<p align="center" id="quote"></p>

<script>
// Animated typing effect
const texts = [
  "React dev & DSA master in the making.",
  "232 days LeetCode grind strong.",
  "Coding my way to the top.",
  "Consistency is the real flex.",
  "Keep calm and code on."
];

let count = 0;
let index = 0;
let currentText = '';
let letter = '';

(function type() {
  if (count === texts.length) count = 0;
  currentText = texts[count];
  letter = currentText.slice(0, ++index);

  document.getElementById('typed-text').innerHTML = letter;
  if (letter.length === currentText.length) {
    count++;
    index = 0;
    setTimeout(type, 1500);
  } else {
    setTimeout(type, 100);
  }
})();

// Random quote generator
const quotes = [
  "Consistency beats talent when talent doesn’t work hard.",
  "Code hard, dream big.",
  "Every line of code is a step closer to greatness.",
  "Debugging is like being a detective in a crime movie.",
  "Keep pushing, keep improving."
];

document.getElementById('quote').innerText = quotes[Math.floor(Math.random() * quotes.length)];
</script>

