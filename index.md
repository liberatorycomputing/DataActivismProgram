---
title: Home
layout: home
---
# Data Activism Program

<img src="/DataActivismProgram/DataActivismLogo.jpg" alt="Data Activism Logo" width="200" height="200"> <br>
Curriculum developed by Raechel Walker

### Overview

This module is focused on the power of quantitative data, and the complexity of thought needed to collect data responsibly.  Datasets of quantitative information are a fundamental part of data-driven decision making, which is a central component of governmental and corporate policy making in the 21st century, whether through the use of Artificial Intelligence (AI), Data Science or Data Analysis. In this module, students will get introduced to the processes of data collection, cleaning and visualization. They will also learn how to apply the tools they learn to critically assess the ways data is used in societal decision making around them. 

Students will begin by learning the basics of Python, before exploring how data is collected, cleaned and aggregated into tabular datasets using Google Sheets. After dataset creation, students will return to using Python, where they learn how to aggregate data for analysis. Combining data analysis and art, students will then create Data Drawings. Finally, students will consider how data is captured about individuals by governmental and social technology systems, and then how they’d like data to express information about themselves. 

Throughout each lesson, students will delve into intersectionality, exploring how various forms of oppression intersect and impact African Americans. Following practice sessions in conducting intersectional data analysis on projects related to their final project, they will embark on learning about the Critical Participatory Action Research Framework (CPAR).  The curriculum includes a range of intersectional data analysis activities aimed at equipping students with the skills to utilize data science in visualizing different forms of oppression, including food insecurity, housing injustice, climate injustice, and affirmative action.  Students will engage in every step of the CPAR framework alongside the community organization they collaborate with. This involves participating in relationship-building activities, formulating research questions, analyzing both qualitative and quantitative data, and ultimately sharing their findings with the community.


### Access Form




<form
  id="accessForm"
  action="https://docs.google.com/forms/d/e/1FAIpQLSc8h1jNpDrwbw9Qlzi8mbPX2txyXgIqzJmrWEy550iJlDO4tw/formResponse"
  method="POST"
  target="hidden_iframe"
  onsubmit="handleAccessFormSubmit(event)"
>
  <label for="name">Name:</label><br />
  <input type="text" name="entry.1039838533" id="name" required /><br /><br />

  <label for="email">Email:</label><br />
  <input type="email" name="entry.1885539352" id="email" required /><br /><br />

  <button type="submit">Get Access</button>
</form>

<iframe name="hidden_iframe" style="display:none;"></iframe>

<script>
  function handleAccessFormSubmit(event) {
    event.preventDefault();

    document.getElementById('accessForm').submit();

    localStorage.setItem("formFilled", "true");

    setTimeout(() => {
      window.location.href = "/DataActivismProgram/";
    }, 1000);
  }
</script>



<script>
  document.addEventListener("DOMContentLoaded", function () {
    if (localStorage.getItem("formFilled") === "true") {
      const sidebar = document.querySelector(".side-bar .nav-list") || document.querySelector(".site-nav .nav-list");

      if (sidebar) {
        const newLink = document.createElement("li");
        newLink.className = "nav-list-item";

        newLink.innerHTML = '<a href="/DataActivismProgram/protected/lesson-1" class="nav-list-link">Lesson 1</a>';

        const existing = sidebar.querySelector('a[href="/DataActivismProgram/protected/lesson-1"]');
        if (!existing) {
          sidebar.appendChild(newLink);
        }
      }
    }
  });
</script>




<a href="https://creativecommons.org">Data Activism Program</a> © 2025 by <a href="https://creativecommons.org">Raechel Walker</a> is licensed under <a href="https://creativecommons.org/licenses/by-nc-sa/4.0/">CC BY-NC-SA 4.0</a><img src="https://mirrors.creativecommons.org/presskit/icons/cc.svg" style="max-width: 1em;max-height:1em;margin-left: .2em;"><img src="https://mirrors.creativecommons.org/presskit/icons/by.svg" style="max-width: 1em;max-height:1em;margin-left: .2em;"><img src="https://mirrors.creativecommons.org/presskit/icons/nc.svg" style="max-width: 1em;max-height:1em;margin-left: .2em;"><img src="https://mirrors.creativecommons.org/presskit/icons/sa.svg" style="max-width: 1em;max-height:1em;margin-left: .2em;">
