
<template>
    <section id="services">
          <div class="container">
              <h1 class="text-left">Fotografia</h1>
              <p class="w-75">
        Ho da sempre nutrito un profondo amore per la fotografia e la sua  capacità di immortalare istanti che rimarranno indelebili nel tempo.
        Amo trascorrere del tempo con le persone, perché sono convinta che ognuna di esse possa regalarmi qualcosa di unico, qualcosa che porterò con me.
        La mia passione per la fotografia mi ha spinto a intraprendere un percorso accademico, dove ho potuto approfondire le tecniche, le teorie, le conoscenze e i segreti di questa meravigliosa forma d'arte. 
        Sono sempre alla ricerca di nuove sfide e di modi creativi per esprimere la mia passione attraverso l'obiettivo.</p>
              <div class="row">
                  <div class="col-lg-4 mt-4">
                      <div class="card servicesText">
                          <div class="card-body">
                              <i class="fas servicesIcon fa-clock"></i>
                              <h4 class="card-title mt-3">Wedding Photography</h4>
                              <p class="card-text mt-3">L'amore, valore in cui credo profondamente. Immortalare i vostri sorrisi, le vostre emozioni nel giorno più importante, rappresenta per me una gioia indescrivibile.
                              </p>
                          </div>
                      </div>  
                  </div>
                  <div class="col-lg-4 mt-4">
                      <div class="card servicesText">
                          <div class="card-body">
                              <i class='fas servicesIcon fa-layer-group'></i>
                              <h4 class="card-title mt-3">Maternity</h4>
                              <p class="card-text mt-3"> Goditi l'attesa tenendo traccia del ricordo della tua gravidanza.
                              </p>
                          </div>
                      </div>  
                  </div>

                  <div class="col-lg-4 mt-4">
                      <div class="card servicesText">
                          <div class="card-body">
                              <i class='far servicesIcon fa-check-circle'></i>
                              <h4 class="card-title mt-3">Baby Shooting</h4>
                              <p class="card-text mt-3"> Per mantenere indelebili nel tempo i primi anni di vita del/la tuo/a Bimbo/a.
                              </p>
                          </div>
                      </div>  
                  </div>
              </div>

              <div class="row">
                  <div class="col-lg-4 mt-4">
                      <div class="card servicesText">
                          <div class="card-body">
                              <i class='fas servicesIcon fa-search'></i>
                              <h4 class="card-title mt-3">Fashion Photography</h4>
                              <p class="card-text mt-3">Arte che cattura l'eleganza, l'espressione e la bellezza del momento</p>
                          </div>
                      </div>  
                  </div>

                  <div class="col-lg-4 mt-4">
                      <div class="card servicesText">
                          <div class="card-body">
                              <i class='fas servicesIcon fa-shield-alt'></i>
                              <h4 class="card-title mt-3">Fotografia Artistica</h4>
                              <p class="card-text mt-3">Per esprimere tutto il valore più profondo della fotografia, attimi bloccati nel tempo e meravigliose composizioni.
                              </p>
                          </div>
                      </div>  
                  </div>

                  <div class="col-lg-4 mt-4">
                      <div class="card servicesText">
                          <div class="card-body">
                              <i class='fas servicesIcon fa-wrench'></i>
                              <h4 class="card-title mt-3">Fotografia di Studio</h4>
                              <p class="card-text mt-3">Fotografie di still life o di ritratto in studio, grazie alla conoscenza dell'utilizzo delle luci edell'attrezzatura.
                              </p>
                          </div>
                      </div>  
                  </div>
              </div>
          </div>
      </section>
</template>

<script>

</script>

<style scoped>
  /* services section css */

  #services{
    margin-top: 4rem;
    margin-bottom: 4rem;
  }
  .servicesText.card {
      height: 190px;
      cursor: pointer;
    }
  .servicesIcon {
      font-size: 36px;
      text-align: center;
      width: 100%;
  }
  .card-title {
      text-align: center;
  }

  .card-text{
  text-align: center
  }

  .card:hover .servicesIcon {
      color: #702a62;
  }
  .servicesText:hover {
      border: 1px solid #702a62;
  }
</style>
