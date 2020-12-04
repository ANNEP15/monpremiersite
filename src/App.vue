
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
        <li>
          <a class="nav-link" href="mailto:annette.plaisimont@sgcib.com" title="Contact">Contact</a>
        </li>
       
        <li class="nav-item active">
          <a class="nav-link" href="#tableau">Tableau <span class="sr-only">Tableau</span></a>
        </li>
        <li class="float-right">
        <img class="float-right" src="./assets/logo.jpg"/>
        </li>
        
                     
            
                       
    </div>
    
  </nav>
                
  <Messages msg="Hello - Bienvenu sur le site d'Annette" />

<div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
  <ol class="carousel-indicators">
    <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
  </ol>
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img class="d-block w-100" src="./assets/femme flamme2.jpg" alt="Tableau 1">
    </div>
    <div class="carousel-item">
      <img class="d-block w-100" src="./assets/MER2.jpg" alt="Second slide">
    </div>
    <div class="carousel-item">
      <img class="d-block w-100" src="..." alt="Third slide">
    </div>
  </div>
  <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
  </a>
</div>

             <!-- Footer -->
 <div id="footer">e-mail </div> 
  <div class="col-sm-4 offset-md-1 py-4">
          
          <ul class="list-unstyled">
              <li><a href="#" class="text-white">Contact</a></li>
          </ul>
        </div>
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