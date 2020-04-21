<template>
  <div class="jumbo container mt-5">
        <div class="jumbotron jumbotron-fluid bg-white">
            <div class="container">
                <h1 class="display-4">Hello, world!</h1>
                <p class="lead">This is a simple hero unit, a simple jumbotron-style component for calling extra attention to featured content or information.</p>
                <hr class="my-4">
                <p>It uses utility classes for typography and spacing to space content out within the larger container.</p>
                <a class="btn btn-primary btn-lg" href="#" role="button">Learn more</a><br><br><br>
                <div class="logo"><img src="./logos/images.png" width="60px"></div>
                <div class="logo"><img src="./logos/mail.png" width="60px"></div>
                <div class="logo"><img src="./logos/rocket.png" width="60px"></div>
                <div class="logo"><img src="./logos/google.png" width="60px"></div>
            </div>
        </div>
        <div class="img">
            <img src="./images/cartoon-doctor.jpg" width="500px">
        </div>
        <div class="clr"></div>
  </div>
</template>

<script>
export default {
    name: "jumbotron"
}
</script>

<style>
.logo{
    padding-left: 20px;
    display: inline;
}
.jumbotron{
    float: left;
    width: 50%;
    box-sizing: border-box;
}
.img{
    float: right;
    width: 50%;
    box-sizing: border-box;
}
@media(max-width:1000px){
    .jumbotron{
        float: none;
        width: 100%;
        box-sizing: border-box;
    }
    .img{
        float: none;
        width: 100%;
        box-sizing: border-box;
    }
}
.clr{
	clear:both;
}

</style>