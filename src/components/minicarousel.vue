<template>
  <div class="container my-5">
        <div id="carouselExampleIndicators" class="minicarousel mt-4 carousel slide" data-ride="carousel">
            <ol class="carousel-indicators">
                <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
                <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
                <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
            </ol>
            <div class="carousel-inner">
                <div class="carousel-item active">
                <img class="d-block w-100" src="./images/carousel1.jpg" alt="First slide">
                </div>
                <div class="carousel-item">
                <img class="d-block w-100" src="./images/carousel2.jpg" alt="Second slide">
                </div>
                <div class="carousel-item">
                <img class="d-block w-100" src="./images/carousel3.jpg" alt="Third slide">
                </div>
            </div>
            <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="sr-only">Previous</span>
            </a>
            <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="sr-only">Next</span>
            </a>
        </div>
        <div class="sidesection mt-3">
            <h1>Look like an expert, right from the start.</h1>
            <p>It’s more then a WordPress theme. It’s like a design tool that let’s you create websites of any niche, easily. Each and every block is created with AB testing and UX research. Take a look at all the pages and elements and see how beautiful your webiste will become. No coding required, ofcourse!</p>
            <button class="btn btn-primary">Discover more</button>
        </div>
        <div class="clr"></div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
img{
    border-radius: 5px;
}
.minicarousel{
    float: left;
    width: 50%;
    box-sizing: border-box;
}
.sidesection{
    padding-left: 25px;
    float: right;
    width: 50%;
    box-sizing: border-box;
}
@media(max-width:1000px){
    .minicarousel{
        float: none;
        width: 100%;
        box-sizing: border-box;
    }
    .sidesection{
        float: none;
        width: 100%;
        box-sizing: border-box;
    }
}
.clr{
	clear:both;
}
</style>