
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
    <div class="collapse navbar-collapse" id="navbarSupportedContent">	     <img src="./assets/logo.jpg"/>
      <ul class="navbar-nav mr-auto">	  </div>
        <li class="nav-item active">	</nav>

  <Messages msg="Hello - Bienvenu sur le site d'Annette" />

<div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
  <ol class="carousel-indicators">
    <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="3"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="4"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="5"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="6"></li>
  </ol>
  <div class="carousel-inner">

    <div class="carousel-item active">
      <img class="w-100" src="./assets/femme flamme1.jpg" alt="Tableau 1">
    </div>
    <div class="carousel-item">
      <img class="w-100" src="./assets/MER.jpg" alt="Second slide">
    </div>
    <div class="carousel-item">
      <img class="w-100" src="./assets/CHEMIN1.jpg" alt="Third slide">
    </div>
      <div class="carousel-item">
      <img class="w-100" src="./assets/FACE.jpg" alt="Fourth slide">
    </div>
    <div class="carousel-item">
      <img class="w-100" src="./assets/TOURBILLON.jpg" alt="Fifth slide">
    </div>
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

<style>
.carousel-control-prev-icon {
    background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' fill='black' viewBox='0 0 8 8'%3E%3Cpath d='M5.25 0l-4 4 4 4 1.5-1.5-2.5-2.5 2.5-2.5-1.5-1.5z'/%3E%3C/svg%3E");
}

.carousel-control-next-icon {
    background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' fill='black' viewBox='0 0 8 8'%3E%3Cpath d='M2.75 0l-1.5 1.5 2.5 2.5-2.5 2.5 1.5 1.5 4-4-4-4z'/%3E%3C/svg%3E");
}

</style>