
<template>

    <section id="contact">
            <div class="container mt-3 contactContent">
                <h1 class="text-left">Contact Me</h1>

                <div class="row mt-4">
                    <div class="col-lg-6">
                        <img src="@/assets/ile_laurea.png" alt="">
                    </div>

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
                        <button type="button" class="btn btn mt-3">Contact Me</button>
                    
                    </div>

                </div>
            </div>
        </section>

   
</template>

<script>

</script>

<style scoped>


img{
    height: 300px;
    width: 300px;
    background-repeat: no-repeat;
    align-items: start;
    text-align: start;
}
#contact{
    background-image: url("@/assets/cerchio2.svg");
    background-position: 10%;
    background-size:31%;
    background-repeat: no-repeat;
    text-align: center;
    align-items: center;
}

.text-left{
    padding-left: 17rem;
    padding-bottom: 2rem;
    padding-top: 2rem;
}

.form-control{
font-size: 10pt;
}

#contactme{
    font-size: 25pt;
}
.btn{
    background-color: rgb(122, 90, 122);
    color: white;
}

</style>
