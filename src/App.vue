
<template>
<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
  <div class="collapse navbar-collapse" id="navbarTogglerDemo03">
    <ul class="navbar-nav mr-auto mt-2 mt-lg-0">
      <li class="nav-item active">
        <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#tableau">Tableau</a>
      </li>
    </ul>

     <img src="./assets/logo.jpg"/>
  </div>
</nav>
  
  <Messages msg="Hello - Bienvenu sur le site d'Annette" />
  <!-- Footer -->
 <div id="footer">Je suis le footer </div> 
<!-- Footer -->
</template>

<script>
import Messages from "./components/Messages.vue";
export default {
  name: "App",
  components: {
    Messages,
  },
};
</script>