<template>
  
  <div>
   <div class="logo">
      <img src="../../assets/Logo_GOES2.png" alt="">
    </div>
  <nav class="navbar navbar-expand-lg bg-dark">
   
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
      <ul class="navbar-nav ml-auto">
        <li class="nav-item a">
          <a class="nav-link" href="#"
            >Vacunación</a
          >
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Existencias</a>
        </li>
        
      
      </ul>
     
    </div>
  </nav>
  </div>
  
</template>

<script>
export default {
  name: 'HeaderComponent'
};
</script>

<style>
  img{
    max-width: 100%;
  }
  .logo{
    background:#313945;;
  }
</style>>