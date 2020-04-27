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
                <i class="fa fa-angle-left fa-3x" aria-hidden="true" style="color:#8080809e;"></i>
                <span class="sr-only">Previous</span>
            </a>
            <a class="carousel-control-next" href="#carouselExampleControls" role="button" data-slide="next">
                <i class="fa fa-angle-right fa-3x" aria-hidden="true" style="color:#8080809e;"></i>
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
p{
    color: gray
}

.carousel {
    .carousel-control-prev, 
    .carousel-control-next {
        transition: 0.3s;
        opacity: 0;
    }
    &:hover {
        .carousel-control-prev, 
        .carousel-control-next {
            opacity: 1;
        }
    }

    i.fa {
        display: inline-block;
        width: 52px;
        height: 52px;
        background: #fff;
        border: 1px solid #ddd;
        border-radius: 50%;
    }
}

</style>