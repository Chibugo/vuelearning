<template>
     
         <nav class="navbar navbar-expand-lg navbar-light bg-primary fixed-top">
             <div class="container">
  <router-link class="navbar-brand" to="#">Navbar</router-link>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  
  <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
    <ul class="navbar-nav">
      <li class="nav-item active">
        <router-link class="nav-link" to="/">Home <span class="sr-only">(current)</span></router-link>
      </li>
      <li class="nav-item">
        <router-link class="nav-link" to="/about">About</router-link>
      </li>
      <li class="nav-item">
        <router-link class="nav-link" to="/contact">Contact</router-link>
      </li>
      <li class="nav-item">
        <router-link class="nav-link disabled" to="/services" tabindex="-1" aria-disabled="true">Services</router-link>
      </li>
    </ul>
  </div>
             </div>
</nav>
 
</template>

<script>
export default {

}
</script>

<style scoped>
.nav-link{
    color: white !important;
}
</style>
