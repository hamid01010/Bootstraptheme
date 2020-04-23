<template>
  <div class="container mb-5">
      <div class="text-center my-5">
          <h1>Let our work do the talking</h1>
          <p>Brands we've successfully made along the way</p>
      </div>


      <ul class="nav nav-pills mb-3" id="pills-tab" role="tablist">
  <li class="nav-item">
    <a class="nav-link active" id="pills-home-tab" data-toggle="pill" href="#pills-home" role="tab" aria-controls="pills-home" aria-selected="true">Home</a>
  </li>
  <li class="nav-item">
    <a class="nav-link" id="pills-profile-tab" data-toggle="pill" href="#pills-profile" role="tab" aria-controls="pills-profile" aria-selected="false">Profile</a>
  </li>
  <li class="nav-item">
    <a class="nav-link" id="pills-contact-tab" data-toggle="pill" href="#pills-contact" role="tab" aria-controls="pills-contact" aria-selected="false">Contact</a>
  </li>
</ul>

<div class="tab-content" id="pills-tabContent">
    <div class="tab-pane fade show active" id="pills-home" role="tabpanel" aria-labelledby="pills-home-tab">
        <div class="row mx-auto">
            <div class="col-lg-4 col-md-4 col-12 mb-4"> 
                <img src="./images/carousel1.jpg" class="img-fluid">
            </div>
            <div class="col-lg-4 col-md-4 col-12 mb-4"> 
                <img src="./images/carousel1.jpg" class="img-fluid">
            </div>
            <div class="col-lg-4 col-md-4 col-12 mb-4"> 
                <img src="./images/carousel1.jpg" class="img-fluid">
            </div>
            <div class="col-lg-4 col-md-4 col-12 mb-4"> 
                <img src="./images/carousel1.jpg" class="img-fluid">
            </div>
            <div class="col-lg-4 col-md-4 col-12 mb-4"> 
                <img src="./images/carousel1.jpg" class="img-fluid">
            </div>
            <div class="col-lg-4 col-md-4 col-12 mb-4"> 
                <img src="./images/carousel1.jpg" class="img-fluid">
            </div>
        </div>
    </div>
  <div class="tab-pane fade" id="pills-profile" role="tabpanel" aria-labelledby="pills-profile-tab">
        <div class="row mx-auto">
            <div class="col-lg-4 col-md-4 col-12 mb-4"> 
                <img src="./images/carousel2.jpg" class="img-fluid">
            </div>
            <div class="col-lg-4 col-md-4 col-12 mb-4"> 
                <img src="./images/carousel2.jpg" class="img-fluid">
            </div>
            <div class="col-lg-4 col-md-4 col-12 mb-4"> 
                <img src="./images/carousel2.jpg" class="img-fluid">
            </div>
            <div class="col-lg-4 col-md-4 col-12 mb-4"> 
                <img src="./images/carousel2.jpg" class="img-fluid">
            </div>
            <div class="col-lg-4 col-md-4 col-12 mb-4"> 
                <img src="./images/carousel2.jpg" class="img-fluid">
            </div>
            <div class="col-lg-4 col-md-4 col-12 mb-4"> 
                <img src="./images/carousel2.jpg" class="img-fluid">
            </div>
        </div>
  </div>
  <div class="tab-pane fade" id="pills-contact" role="tabpanel" aria-labelledby="pills-contact-tab">
        <div class="row mx-auto">
            <div class="col-lg-4 col-md-4 col-12 mb-4"> 
                <img src="./images/carousel3.jpg" class="img-fluid">
            </div>
            <div class="col-lg-4 col-md-4 col-12 mb-4"> 
                <img src="./images/carousel3.jpg" class="img-fluid">
            </div>
            <div class="col-lg-4 col-md-4 col-12 mb-4"> 
                <img src="./images/carousel3.jpg" class="img-fluid">
            </div>
            <div class="col-lg-4 col-md-4 col-12 mb-4"> 
                <img src="./images/carousel3.jpg" class="img-fluid">
            </div>
            <div class="col-lg-4 col-md-4 col-12 mb-4"> 
                <img src="./images/carousel3.jpg" class="img-fluid">
            </div>
            <div class="col-lg-4 col-md-4 col-12 mb-4"> 
                <img src="./images/carousel3.jpg" class="img-fluid">
            </div>
        </div>
  </div>
</div>


  </div>
</template>

<script>
export default {
    name: "gallary"
}
</script>

<style scoped>
img{
    border-radius: 5px;
    width: 500px;
}
ul{
    width: 250px;
    margin: auto
}
</style>