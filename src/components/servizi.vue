
<template>
    <section id="services">
          <div class="container">
              <h1 class="text-left">Grafica</h1>
              <div class="row">
                  <div class="col-lg-4 mt-4">
                      <div class="card servicesText">
                          <div class="card-body">
                              <i class="fas servicesIcon fa-clock"></i>
                              <h4 class="card-title mt-3">Ux e UI designer</h4>
                              <p class="card-text mt-3">Progettazione User Experience e User Interface di Applicazioni.
                              </p>
                          </div>
                      </div>  
                  </div>
                  <div class="col-lg-4 mt-4">
                      <div class="card servicesText">
                          <div class="card-body">
                              <i class='fas servicesIcon fa-layer-group'></i>
                              <h4 class="card-title mt-3">Website Design</h4>
                              <p class="card-text mt-3"> Progettazione User Interface di Siti web e Landing page.
                              </p>
                          </div>
                      </div>  
                  </div>

                  <div class="col-lg-4 mt-4">
                      <div class="card servicesText">
                          <div class="card-body">
                              <i class='far servicesIcon fa-check-circle'></i>
                              <h4 class="card-title mt-3">Grafica Tradizionale</h4>
                              <p class="card-text mt-3">Rebranding Loghi, Creazione Loghi, Design di brochure, Inviti e molto altro.
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
                              <h4 class="card-title mt-3">Pacchetto Adobe</h4>
                              <p class="card-text mt-3"> Ho una buona conoscenza del pacchetto Adobe (Photoshop, Illustartor, Indesign, Lightroom, After Effects, Animate).
                              </p>
                          </div>
                      </div>  
                  </div>

                  <div class="col-lg-4 mt-4">
                      <div class="card servicesText">
                          <div class="card-body">
                              <i class='fas servicesIcon fa-shield-alt'></i>
                              <h4 class="card-title mt-3">Montaggio video</h4>
                              <p class="card-text mt-3">Buona conoscenza di Davinci resolve per il montaggio video.
                              </p>
                          </div>
                      </div>  
                  </div>

                  <div class="col-lg-4 mt-4">
                      <div class="card servicesText">
                          <div class="card-body">
                              <i class='fas servicesIcon fa-wrench'></i>
                              <h4 class="card-title mt-3">Siti web</h4>
                              <p class="card-text mt-3">Conoscenza base di html, css, javascritp. Buona conoscenza di Wordpress (Elementor pro) e Webflow
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
      height: 170px;
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
