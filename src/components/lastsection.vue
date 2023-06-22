
<template>
    

    <div id="footer" class="container-fluid text-center">
      <div class="row align-items-center">
        <div class="col">
             <img id="logo" src="@/assets/logoile.png" height="80" width="80" alt="">
           <p>Privacy Policy</p>
           <p>Termini e condizioni</p>
        </div>
        <div class="col">
            <h5>Contatti</h5>
            <p>Email: ileniacauchioli@gamil.com</p>
            <p>Telefono: 3421602355</p>
        </div>
        <div class="col">
           <div class="title_social">
           <h5>Seguimi sui social</h5>
        </div>
        <div class="social-icons">
            <a href="https://www.instagram.com/ilenia_cauchioli.ph/" target="_blank"><i class="fab fa-instagram">
                <img src="@/assets/instagram.png" id="insta" height="46" width="40" alt="">
            </i></a>
            <a href="https://www.linkedin.com/in/ilenia-cauchioli/" target="_blank"><i class="fab fa-linkedin">
                 <img src="@/assets/linkedin.png" id="linke" height="40" width="40" alt="">
            </i></a>
         </div>
        </div>
      </div>
    </div>
    
</template>

<script>

</script>

<style scoped>
p{
   font-size: 10pt;
   color: white;
}

h5{
    color: white;
    padding-bottom: 0.5rem;
}

#logo{
    margin-bottom: 1rem;
    margin-top: 2rem;
}

#insta{
margin-right: 1rem;
}

#linke{
margin-right: 1rem; 
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
    height: 50%;
    margin-top: 2rem;
    padding-bottom: 2rem;
}
</style>
