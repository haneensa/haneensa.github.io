---
layout: about
---


<div class="about-title">Haneen [حنين]</div>

---

<div class="about-nav">
<a href="https://github.com/haneensa" target="_blank">GitHub</a>
<a href="https://drive.google.com/file/d/0B0B0K8GnwBGnVXhBREI3YjJVaGc/view?usp=share_link&resourcekey=0-omQO5cSa3Qnj0_-PIKtpBg" target="_blank">CV</a>
<a href="https://www.linkedin.com/in/haneenmohammed/" target="_blank">LinkedIn</a>
<a href="http://haninjafoto.tumblr.com/" target="_blank">Photos</a>
</div>

---


Updates:
<nav>
<ul>
  {% for update in site.data.updates %}
  <li>
[ {{ update.date }} ] {{ update.title }}!
  </li>
  {% endfor %}
</ul>
</nav>
