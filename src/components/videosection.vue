<template>
  <div class="container my-5">
    <br>  
    <h1 class="text-center">A product for every niche</h1>
    <p class="text-center">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Nihil pariatur</p>  
    <div class="embed-responsive embed-responsive-16by9 vid mt-4">
        <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/zpOULjyy-n8?rel=0" allowfullscreen></iframe>
    </div>
    <div class="sidesection">
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
        float: left;
        width: 50%;
        box-sizing: border-box;
    }
    .sidesection{
        padding: 50px 20px 50px 50px;
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