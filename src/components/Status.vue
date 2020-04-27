<template>
  <div class="container mb-5">
      <div class="text-center my-5">
          <h1>Fun facts from workspace</h1>
          <p>We’re hustlers, we get shit done no matter what</p>
      </div>

      <div class="card-deck">
  <div class="card">
    <div class="card-body">
      <i class="fa fa-window-maximize" aria-hidden="true"></i>  
      <h1 class="card-title">230</h1>
      <p class="card-text">Website Created</p>
    </div>
  </div>
  <div class="card">
    <div class="card-body">
      <i class="fa fa-clone" aria-hidden="true"></i>  
      <h1 class="card-title">34</h1>
      <p class="card-text">Cloud Apps Built</p>
    </div>
  </div>
  <div class="card">
    <div class="card-body">
      <i class="fa fa-clock-o" aria-hidden="true"></i>  
      <h1 class="card-title">72+</h1>
      <p class="card-text">Projects Completed</p>
    </div>
  </div>
  <div class="card">
    <div class="card-body">
      <i class="fa fa-heart-o" aria-hidden="true"></i>  
      <h1 class="card-title">14k</h1>
      <p class="card-text">Likes on Dribbble</p>
    </div>
  </div>
</div>
  </div>
</template>

<script>
export default {
    name: "Status"
}
</script>

<style scoped>
i{
    color: blue
}
p{
    color: gray;
}
.card{
    transition: .6s;
    height: 160px;
}
.card:hover{
    margin-top: -10px;
    box-shadow: 0px 10px 15px #efefef;
}
</style>