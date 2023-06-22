
<script setup>
</script>


<template>

  <nav class="navbar navbar-expand-lg fixed-top navbarScroll">
          <div class="container">
              <a class="navbar-brand" href="#">
                <img class="logo" src="@/assets/logoile.png" alt="Logo"/>
              </a>
              <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                  <span class="navbar-toggler-icon"></span>
              </button>
              <div class="collapse navbar-collapse" id="navbarSupportedContent">
                  <ul class="navbar-nav ms-auto">
                      <li class="nav-item active">
                          <a class="nav-link" href="#home">Home</a>
                      </li>
                      <li class="nav-item">
                          <a class="nav-link" href="#services">Portfolio</a>
                      </li>
                      <li class="nav-item">
                          <a class="nav-link" href="#contact">Contact</a>
                      </li>
                  </ul>
                
              </div>
          </div>
      </nav>
</template>

<style scoped>
.logo {
  position: static;
  width: 50px;
  height: 50px;
}

.navbar{
  background-color:  rgb(202, 170, 156);
}
</style>
