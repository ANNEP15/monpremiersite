
<template>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <button
      class="navbar-toggler"
      type="button"
      data-toggle="collapse"
      data-target="#navbarSupportedContent"
      aria-controls="navbarSupportedContent"
      aria-expanded="false"
      aria-label="Toggle navigation"
    >
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item active">
          <a class="nav-link" href="#">Home <span class="sr-only">Home</span></a>
        </li>
        <li class="nav-item active">
          <a class="nav-link" href="#tableau">Tableau <span class="sr-only">Tableau</span></a>
        </li>
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