<template>
  <div class="bg-dark text-white ribbon">
            <div class="container py-4">
                <div>
                    <h3>Ready to revolutionize your website?</h3>
                    <button class="btn btn-light"><b class="text-muted">Discover more</b></button>
                </div>
                <div class="clr"></div>
            </div>
  </div>
</template>

<script>
export default {
    name: "Ribbon"
}
</script>

<style scoped>
.ribbon{
    border-bottom: 1px solid gray;
}
h3{
    float: left;
    width: 85%;
    box-sizing: border-box;
}
button{
    float: right;
    width: 15%;
    border-radius: 20px;
    box-sizing: border-box;
}
@media(max-width:1000px){
    h3{
        float: none;
        width: 100%;
        box-sizing: border-box;
    }
    button{
        float: none;
        width: 40%;
        margin: auto;
        box-sizing: border-box;
    }
}
.clr{
	clear:both;
}
</style>