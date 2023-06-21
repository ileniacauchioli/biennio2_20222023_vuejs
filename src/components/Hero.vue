<script setup>

</script>

<template>
      
      <section class="bgimage" id="home">
          <div class="container-fluid">
              <div class="row">
              <div class="col-lg-12 col-md-12 col-sm-12 col-xs-12 hero-text">
                  <h2 class="hero_title">My Portfolio</h2>
                  <p class="hero_desc">Graphic and Photography</p>
              </div>
              </div>
          </div>
      </section>

    
</template>

<style scoped>

.bgimage {
    height:100vh;
    background: url('./src/assets/Sfondoherocorretto.png');
    background-size:cover;
    position:relative;
}

/* text css above hero image*/
.hero_title {
    font-size: 4.5rem;
}
.hero_desc {
    font-size: 2rem;
}
.hero-text {
    text-align: center;
    position: absolute;
    margin-top: 20rem;
    color: rgb(103, 78, 78);
}
</style>
