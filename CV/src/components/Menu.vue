<template>
<nav>
  <ul>
    <li>
        <router-link to="/"><img class="nav-icons" src="../assets/images/Home.png"></router-link>
    </li>
    <li><p>Accueil</p></li>
    <li>
        <router-link to="/Projets"><img class="nav-icons" src="../assets/images/Projects.png"></router-link>
    </li>
    <li><p>Projets</p></li>
    <li>
        <router-link to="/CV"><img class="nav-icons" src="../assets/images/CV.png"></router-link>
    </li>
    <li><p>CV</p></li>
    <li>
       <router-link to="/Contact"><img class="nav-icons" src="../assets/images/Contact.png"></router-link>
    </li>
    <li><p>Contact</p></li>
  </ul>
</nav>
</template>



<style scoped>

nav {
        float: left;
        margin-left: 50px;
    }
    
    nav ul {
        text-align: center;
    }
    
    .nav-icons {
        width: 80px;
        height: 80px;
    }

    p {
        color: white;
        font-family: Big Pixel;
        font-size: 20px;
        font-weight: bold;
        margin-bottom: 10px;
    }
</style>