<template>
  <div class="container mb-5">
    <div class="text-center my-5">  
        <h1>A product for every niche</h1>
        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Nihil pariatur</p>
    </div>  
    <div class="embed-responsive embed-responsive-16by9 vid">
        <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/l482T0yNkeo" allowfullscreen></iframe>
    </div>
    <div class="sidesection mt-4">
        <div>
            <h4>Lorem ipsum dolor</h4>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nam, qui accusantium, voluptatem tempora corrupti voluptatibus iure ex sit facere laborum</p>
        </div>
        <div>
            <h4>Lorem ipsum dolor</h4>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nam, qui accusantium, voluptatem tempora corrupti voluptatibus iure ex sit facere laborum</p>
        </div>
    </div>
    <div class="clr"></div>
  </div>
</template>

<script>
export default {
    name: "videosection"
}
</script>

<style>
    .vid{
        border-radius: 5px;
        float: left;
        width: 50%;
        box-sizing: border-box;
    }
    .sidesection{
        padding-left: 30px;
        float: right;
        width: 50%;
        box-sizing: border-box;
    }
    @media(max-width:1000px){
        .vid{
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