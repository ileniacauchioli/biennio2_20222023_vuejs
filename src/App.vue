<script >

import Header from './components/Header.vue'
import PortfolioItem from './components/PortfolioItem.vue'
import contentsData from './assets/contents.json'
import NavBar from './components/NavBar.vue'
import Graphic from './components/Graphic.vue'
import Hero from './components/Hero.vue'
import About from './components/About.vue'
import servizi from './components/servizi.vue'
import fotografia from './components/fotografia.vue'
import contatti from './components/contatti.vue'
import lastsection from './components/lastsection.vue'




export default {
  data() {
    return {
      contents: contentsData,
    };
  },
  components: {
    Header,
    PortfolioItem,
    NavBar,
    Graphic,
    Hero,
    About,
    servizi,
    fotografia,
    contatti,
   lastsection,
  },
};

</script> 

<template>
  <main>
    <NavBar />
    <Hero />
    <About/>
    <servizi/>

    <Graphic/>
       <div id="Graphic" class="row">
          <div class="col-12 col-md-2" v-for="work in contents.graphic" :key="work.id">
             <PortfolioItem 
              :imageUrl="work.image_thumbnail"
            />
          </div>
        </div>
  
        <fotografia/>

    <Header />

    <div id="works" class="row">
      <div class="col-12 col-md-2" v-for="work in contents.works" :key="work.id">
         <PortfolioItem 
          :imageUrl="work.image_thumbnail"
        />
      </div>
    </div>

    


    <div id="social-links" class="row">
      <ul>
        <li v-for="link in contents.social_links" :key="link.id">
          <SocialLink 
            :id="link.id"
            :name="link.name"
            :url="link.url"
          />
        </li>
      </ul>
    </div>
    <contatti/>
    <lastsection/>
  </main>
</template>

<style scoped>
#works{
  padding-left: 4rem;
  padding-right: 4rem;
}


#Graphic{
  padding-left: 4rem;
  padding-right: 4rem;
}

NavBar{
  background-color: rgb(213, 173, 156);
  height: 4rem;
}

header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}


</style>
