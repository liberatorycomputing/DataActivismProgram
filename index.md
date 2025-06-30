---
title: Home
layout: home
---
# Data Activism Program

<img src="Rwalker.jpg" alt="Raechel Walker" width="200" height="200"> <br>
Curriculum developed by Raechel Walker

### Overview

This module is focused on the power of quantitative data, and the complexity of thought needed to collect data responsibly.  Datasets of quantitative information are a fundamental part of data-driven decision making, which is a central component of governmental and corporate policy making in the 21st century, whether through the use of Artificial Intelligence (AI), Data Science or Data Analysis. In this module, students will get introduced to the processes of data collection, cleaning and visualization. They will also learn how to apply the tools they learn to critically assess the ways data is used in societal decision making around them. 

Students will begin by learning the basics of Python, before exploring how data is collected, cleaned and aggregated into tabular datasets using Google Sheets. After dataset creation, students will return to using Python, where they learn how to aggregate data for analysis. Combining data analysis and art, students will then create Data Drawings. Finally, students will consider how data is captured about individuals by governmental and social technology systems, and then how they’d like data to express information about themselves. 

Throughout each lesson, students will delve into intersectionality, exploring how various forms of oppression intersect and impact African Americans. Following practice sessions in conducting intersectional data analysis on projects related to their final project, they will embark on learning about the Critical Participatory Action Research Framework (CPAR).  The curriculum includes a range of intersectional data analysis activities aimed at equipping students with the skills to utilize data science in visualizing different forms of oppression, including food insecurity, housing injustice, climate injustice, and affirmative action.  Students will engage in every step of the CPAR framework alongside the community organization they collaborate with. This involves participating in relationship-building activities, formulating research questions, analyzing both qualitative and quantitative data, and ultimately sharing their findings with the community.

{% raw %}
<!-- Firebase App (Core) -->
<script src="https://www.gstatic.com/firebasejs/10.12.0/firebase-app.js"></script>

<!-- Firebase Auth -->
<script src="https://www.gstatic.com/firebasejs/10.12.0/firebase-auth.js"></script>

<script>
  // Your Firebase config (from Firebase console > Project Settings)
  const firebaseConfig = {
    apiKey: "AIzaSyDI37RszOq8_iWzQE0UK6axFjflqvQTbl0",
    authDomain: "liberatorycomputing-16020.firebaseapp.com",
    projectId: "liberatorycomputing-16020",
    storageBucket: "liberatorycomputing-16020.firebasestorage.app",
    messagingSenderId: "572560031507",
    appId: "1:572560031507:web:43a76638a0261a6d84e4e6"
  };
  firebase.initializeApp(firebaseConfig);


  const provider = new firebase.auth.GoogleAuthProvider();

  function signInWithGoogle() {
    firebase.auth().signInWithPopup(provider)
      .then(result => {
        const user = result.user;
        console.log("Logged in as:", user.displayName);
        window.location.href = "/protected.html"; // redirect to protected page
      })
      .catch(error => {
        console.error("Error:", error);
        alert(error.message);
      });
  }
</script>
{% endraw %}


<button onclick="signInWithGoogle()">Sign in with Google</button>




<a href="https://creativecommons.org">Data Activism Program</a> © 2025 by <a href="https://creativecommons.org">Raechel Walker</a> is licensed under <a href="https://creativecommons.org/licenses/by-nc-sa/4.0/">CC BY-NC-SA 4.0</a><img src="https://mirrors.creativecommons.org/presskit/icons/cc.svg" style="max-width: 1em;max-height:1em;margin-left: .2em;"><img src="https://mirrors.creativecommons.org/presskit/icons/by.svg" style="max-width: 1em;max-height:1em;margin-left: .2em;"><img src="https://mirrors.creativecommons.org/presskit/icons/nc.svg" style="max-width: 1em;max-height:1em;margin-left: .2em;"><img src="https://mirrors.creativecommons.org/presskit/icons/sa.svg" style="max-width: 1em;max-height:1em;margin-left: .2em;">
