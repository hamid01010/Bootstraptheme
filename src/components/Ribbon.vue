<template>
  <div class="ribbon">
            <div class="container py-5">
                <div>
                    <h5>Ready to revolutionize your website?</h5>
                    <button class="btn btn-light"><b>Discover more</b></button>
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
    background: #141414;
    border-bottom: 1px solid rgba(83, 81, 81, 0.63);
}
h5{
    color: gray;
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
    h5{
        text-align: center;
        float: none;
        width: 100%;
        margin-bottom: 15px;
        box-sizing: border-box;
    }
    button{
        float: none;
        margin-left: 32%;
        width: 150px;
        box-sizing: border-box;
    }
}
.clr{
	clear:both;
}
</style>