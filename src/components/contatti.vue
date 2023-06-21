
<template>
   <section id="contact">
          <div class="container mt-3 contactContent">
              <h1 class="text-left align-items">Contact Me</h1>

                  <div class="col-lg-6">
                      <!-- form fields -->
                      <form>
                          <input type="text" class="form-control form-control-lg" placeholder="Name">
                          <input type="email" class="form-control mt-3" placeholder="Email">
                          <input type="text" class="form-control mt-3" placeholder="Subject">
                          <div class="mb-3 mt-3">
                              <textarea class="form-control" rows="5" id="comment" name="text" placeholder="Project Details"></textarea>
                          </div>
                      </form>
                      <button type="button" class="btn btn-success mt-3">Send</button>
                   </div>

              </div>

      </section>
</template>

<script>

</script>

<style scoped>
.card{
    background-color: rgb(202, 170, 156);
}

.social-icons {
    font-size: 36px;
    cursor: pointer;
}
.fa-facebook:hover,.fa-instagram:hover,.fa-twitter:hover,.fa-linkedin:hover, .fa-twitch:hover {
    color: #8c6183;
}
.fab {
    color: #000000;
}
/* footer styling */
#footer {
    background-color: rgb(202, 170, 156);
    text-align: center;
}
</style>
