---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<!-- Profile Section with Flexbox -->
<div style="display: flex; align-items: center; gap: 20px; margin-bottom: 30px;">
  <!-- Profile Picture -->
  <img src="https://github.com/{{ site.github_username }}.png" alt="Profile Picture" style="width: 150px; height: 150px; border-radius: 50%;" />
  
  <!-- Profile Info -->
  <div>
    <h1>Nice! you made it here. I'm Ngan! 👋</h1>
    <!-- GitHub Follow Button -->
    <div style="display: flex; flex-direction: column; gap: 10px;">
      <span>
        Software Engineer at Blinq
      </span>
      <a href="https://github.com/{{ site.github_username }}" target="_blank">
        <img src="https://img.shields.io/github/followers/{{ site.github_username }}?label=Follow&style=social" alt="Follow" />
      </a>

    </div>
  </div>
</div>

<div style="display: flex; flex-wrap: wrap; gap: 20px; justify-content: center;">
  <!-- GitHub Contribution Graph -->
  <img src="https://ghchart.rshah.org/{{ site.github_username }}" alt="GitHub Contribution Graph" />

  <!-- GitHub Top Languages -->
  <!-- <img src="https://github-readme-stats.vercel.app/api/top-langs/?username={{ site.github_username }}&layout=compact&theme=shadow_blue" alt="Top Languages" /> -->
</div>

<br>


