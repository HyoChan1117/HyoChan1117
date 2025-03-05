<div align="center">
<br><br><br>

<!-- Don't just fork or copy it. Star it, please 🥺  -->

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Permanent+Marker&size=47&duration=3500&pause=5000&color=72C843&vCenter=true&width=500&height=60&lines=Hi%F0%9F%91%8B%F0%9F%98%8A%2C+I'm+HyoChan!)](https://git.io/typing-svg)

<br><br>

<p align="center">
  <img height="180em" id="streak-stats" alt="HyoChan1117 Streak Stats" />
  <img height="180em" id="top-langs" alt="HyoChan1117 Top Languages" />
</p>

<img id="profile-details" alt="Profile Details" />
<img id="stats" alt="Stats" />
<img id="productive-time" alt="Productive Time" />

<br>

![](./profile-3d-contrib/profile-green.svg)

<script>
  function updateTheme() {
    const isDarkMode = window.matchMedia("(prefers-color-scheme: dark)").matches;
    const theme = isDarkMode ? "dark" : "default";

    document.getElementById("streak-stats").src = `https://github-readme-streak-stats.herokuapp.com/?user=HyoChan1117&theme=${theme}`;
    document.getElementById("top-langs").src = `https://github-readme-stats.vercel.app/api/top-langs/?username=HyoChan1117&layout=compact&theme=${theme}`;
    document.getElementById("profile-details").src = `http://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=HyoChan1117&theme=${theme}`;
    document.getElementById("stats").src = `http://github-profile-summary-cards.vercel.app/api/cards/stats?username=HyoChan1117&theme=${theme}`;
    document.getElementById("productive-time").src = `http://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=HyoChan1117&theme=${theme}`;
  }

  updateTheme();
  window.matchMedia("(prefers-color-scheme: dark)").addEventListener("change", updateTheme);
</script>
