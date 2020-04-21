<template>
    <div class="container">
        <div class="cards">
<div class="row row-cols-1 row-cols-md-2">
  <div class="col mb-4">
    <div class="card">
      
      <div class="card-body">
        <h5 class="card-title">Card title</h5>
        <p class="card-text">This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
      </div>
    </div>
  </div>
  <div class="col mb-4">
    <div class="card">
      
      <div class="card-body">
        <h5 class="card-title">Card title</h5>
        <p class="card-text">This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
      </div>
    </div>
  </div>
  <div class="col mb-4">
    <div class="card">
      
      <div class="card-body">
        <h5 class="card-title">Card title</h5>
        <p class="card-text">This is a longer card with supporting text below as a natural lead-in to additional content.</p>
      </div>
    </div>
  </div>
  <div class="col mb-4">
    <div class="card">
      
      <div class="card-body">
        <h5 class="card-title">Card title</h5>
        <p class="card-text">This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
      </div>
    </div>
  </div>
</div>
        </div>
        <div class="sidebar">
            <h1>Lorem ipsum dolor sit amet consectetur</h1>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Atque sunt nam, ipsam tempora ea neque temporibus laborum! Ipsam sapiente ab veniam perferendis voluptas, quia ratione rem velit iure placeat quo.</p>
            <button class="btn btn-primary">Take 1-min tour</button>
        </div>
        <div class="clr"></div>
    </div>
</template>

<script>
export default {
    name: "cardsection"
}
</script>

<style>
.cards{
    float: left;
    width: 50%;
    box-sizing: border-box;
}
.sidebar{
    float: right;
    width: 50%;
    box-sizing: border-box;
}
@media(max-width:1000px){
    .cards{
        float: none;
        width: 100%;
        box-sizing: border-box;
    }
    .sidebar{
        float: none;
        width: 100%;
        box-sizing: border-box;
    }
}
.clr{
	clear:both;
}
</style>