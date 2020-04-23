<template>
  <div class="container mb-5">
        <div class="text-center my-5">
            <h1>But don’t take our work for it</h1>
            <p>See what people have to say about our product</p>
        </div>
        <div id="carouselExampleControls" class="carousel slide" data-ride="carousel">
            <div class="carousel-inner">
                <div class="carousel-item active">
                    <card />
                </div>
                <div class="carousel-item">
                    <card />
                </div>
                <div class="carousel-item">
                    <card />
                </div>
            </div>
            <a class="carousel-control-prev" href="#carouselExampleControls" role="button" data-slide="prev">
                <span class="carousel-control-prev-icon bg-dark" aria-hidden="true"></span>
                <span class="sr-only">Previous</span>
            </a>
            <a class="carousel-control-next" href="#carouselExampleControls" role="button" data-slide="next">
                <span class="carousel-control-next-icon bg-dark" aria-hidden="true"></span>
                <span class="sr-only">Next</span>
            </a>
        </div>
  </div>
</template>

<script>
import card from "./carouselcard"
export default {
    name: "carouselsection",
    components:{
        card
    }
}
</script>

<style lang="scss" scoped>
.carousel-control-prev-icon, .carousel-control-next-icon{
    height: 32px;
    width: 25px;
    padding: 10px;
    border-radius: 5px;
}
</style>