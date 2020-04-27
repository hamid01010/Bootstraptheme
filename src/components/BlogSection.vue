<template>
  <div class="container mb-5">
      <div class="text-center my-5">
          <h1>Latest reads from blog</h1>
          <p>See what we're up to on a rainy night</p>
      </div>

      <div class="card-deck">
  <div class="card">
    <img class="card-img-top" src="https://cdn.pixabay.com/photo/2020/04/22/06/47/hydrangea-5076212_960_720.jpg" alt="Card image cap">
    <div class="card-body">
      <h5 class="card-title">Card title</h5>
      <p class="card-text">This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
      <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
    </div>
  </div>
  <div class="card">
    <img class="card-img-top" src="https://cdn.pixabay.com/photo/2015/06/08/15/11/typewriter-801921_960_720.jpg" alt="Card image cap">
    <div class="card-body">
      <h5 class="card-title">Card title</h5>
      <p class="card-text">This card has supporting text below as a natural lead-in to additional content.</p>
      <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
    </div>
  </div>
  <div class="card">
    <img class="card-img-top" src="https://cdn.pixabay.com/photo/2015/12/19/20/32/paper-1100254_960_720.jpg" alt="Card image cap">
    <div class="card-body">
      <h5 class="card-title">Card title</h5>
      <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This card has even longer content than the first to show that equal height action.</p>
      <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
    </div>
  </div>
</div>

  </div>
</template>

<script>
export default {
    name: "BlogSection"
}
</script>

<style scoped>
p{
    color: gray;
}
.card{
    height: 500px;
    transition: 0.5s;
}
.card:hover{
    margin-top: -10px;
    box-shadow: 0px 10px 15px rgb(214, 212, 212);
}
</style>