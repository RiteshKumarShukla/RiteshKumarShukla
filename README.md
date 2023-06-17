<h1 align="center">Hi there! 👋 I'm Ritesh Kumar Shukla</h1>
<h3 align="center">
  <span id="typewriter"></span>
  <script>
    const typewriter = document.getElementById("typewriter");
    const titles = [
      "MERN Stack Developer",
      "Software Developer",
      "React Js Developer",
      "Front End Developer"
    ];
    let index = 0;
    let charIndex = 0;
    let isDeleting = false;

    function type() {
      const title = titles[index];
      if (isDeleting) {
        typewriter.textContent = title.substring(0, charIndex - 1);
        charIndex--;
      } else {
        typewriter.textContent = title.substring(0, charIndex + 1);
        charIndex++;
      }

      if (!isDeleting && charIndex === title.length) {
        isDeleting = true;
        setTimeout(type, 2000);
      } else if (isDeleting && charIndex === 0) {
        isDeleting = false;
        index++;
        if (index === titles.length) {
          index = 0;
        }
        setTimeout(type, 500);
      } else {
        setTimeout(type, 100);
      }
    }

    type();
  </script>
</h3>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=riteshkumarshukla&label=Profile%20Views&color=blueviolet&style=flat-square" alt="Profile Views" />
</p>

<p align="center">
  <a href="https://riteshkumarshukla.github.io/" target="_blank">Portfolio</a> •
  <a href="mailto:riteshshuklagem@gmail.com">Contact</a>
</p>

---

<p align="center">
  <a href="https://linkedin.com/in/https://www.linkedin.com/in/ritesh-shukla-1990b4202/">
    <img src="https://img.shields.io/badge/LinkedIn-ritesh--shukla-%230177B5?style=flat-square&logo=linkedin">
  </a>
  <a href="https://codesandbox.com/riteshkumarshukla">
    <img src="https://img.shields.io/badge/CodeSandbox-riteshkumarshukla-%23F0812B?style=flat-square&logo=codesandbox">
  </a>
  <a href="https://www.leetcode.com/ritesh__shukla">
    <img src="https://img.shields.io/badge/LeetCode-ritesh__shukla-%23FFA116?style=flat-square&logo=leetcode">
  </a>
</p>

---

## 💻 Tech Stack

<p align="center">
  <img src="https://img.shields.io/badge/CSS3-%231572B6?style=for-the-badge&logo=css3&logoColor=white">
  <img src="https://img.shields.io/badge/HTML5-%23E34F26?style=for-the-badge&logo=html5&logoColor=white">
  <img src="https://img.shields.io/badge/JavaScript-%23323330?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E">
  <img src="https://img.shields.io/badge/Node.js-%2343853D?style=for-the-badge&logo=node.js&logoColor=white">
  <img src="https://img.shields.io/badge/ChakraUI-%234ED1C5?style=for-the-badge&logo=chakraui&logoColor=white">
  <img src="https://img.shields.io/badge/Express.js-%23404d59?style=for-the-badge&logo=express&logoColor=%2361DAFB">
  <img src="https://img.shields.io/badge/NPM-%23000000?style=for-the-badge&logo=npm&logoColor=white">
  <img src="https://img.shields.io/badge/Styled Components-%23DB7093?style=for-the-badge&logo=styled-components&logoColor=white">
  <img src="https://img.shields.io/badge/React Router-%23CA4245?style=for-the-badge&logo=react-router&logoColor=white">
  <img src="https://img.shields.io/badge/Redux-%23593d88?style=for-the-badge&logo=redux&logoColor=white">
  <img src="https://img.shields.io/badge/React-%2320232a?style=for-the-badge&logo=react&logoColor=%2361DAFB">
  <img src="https://img.shields.io/badge/Bootstrap-%23563D7C?style=for-the-badge&logo=bootstrap&logoColor=white">
  <img src="https://img.shields.io/badge/MongoDB-%234ea94b?style=for-the-badge&logo=mongodb&logoColor=white">
  <img src="https://img.shields.io/badge/Canva-%2300C4CC?style=for-the-badge&logo=Canva&logoColor=white">
  <img src="https://img.shields.io/badge/Notion-%23000000?style=for-the-badge&logo=notion&logoColor=white">
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white">
</p>

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=RiteshKumarShukla&show_icons=true&theme=midnight-purple&hide_border=true" alt="GitHub Stats" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=RiteshKumarShukla&theme=midnight-purple&hide_border=true" alt="GitHub Streak" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=RiteshKumarShukla&layout=compact&theme=midnight-purple&hide_border=true" alt="Top Languages" />
</p>

---

## 🏆 GitHub Trophies

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=RiteshKumarShukla&theme=radical&no-frame=true&no-bg=true&margin-w=4" alt="GitHub Trophies" />
</p>

---

## ✍ Random Dev Quote

<p align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical" alt="Random Dev Quote" />
</p>

---

## 🔝 Top Contributed Repo

<p align="center">
  <img src="https://github-contributor-stats.vercel.app/api?username=RiteshKumarShukla&limit=5&theme=dark&combine_all_yearly_contributions=true" alt="Top Contributed Repo" />
</p>
