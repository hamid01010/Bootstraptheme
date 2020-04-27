<template>
    <div class="bg-dark text-white">
        <footer class="container">
            <div class="ribbon py-4">
                <div>
                    <h3>Ready to revolutionize your website?</h3>
                    <button class="btn btn-light"><b class="text-muted">Discover more</b></button>
                </div>
                <div class="clr"></div>
            </div>  
        <div class="row">
        <div class="col-12 col-md">
            <img class="mb-2" src="/docs/4.4/assets/brand/bootstrap-solid.svg" alt="" width="24" height="24">
            <small class="d-block mb-3 text-white">&copy; 2017-2019</small>
        </div>
        <div class="col-6 col-md">
            <h5>Features</h5>
            <ul class="list-unstyled text-small">
            <li><a href="#">Cool stuff</a></li>
            <li><a href="#">Random feature</a></li>
            <li><a href="#">Team feature</a></li>
            <li><a href="#">Stuff for developers</a></li>
            <li><a href="#">Another one</a></li>
            <li><a href="#">Last time</a></li>
            </ul>
        </div>
        <div class="col-6 col-md">
            <h5>Resources</h5>
            <ul class="list-unstyled text-small">
            <li><a href="#">Resource</a></li>
            <li><a href="#">Resource name</a></li>
            <li><a href="#">Another resource</a></li>
            <li><a href="#">Final resource</a></li>
            </ul>
        </div>
        <div class="col-6 col-md">
            <h5>About</h5>
            <ul class="list-unstyled text-small">
            <li><a href="#">Team</a></li>
            <li><a href="#">Locations</a></li>
            <li><a href="#">Privacy</a></li>
            <li><a href="#">Terms</a></li>
            </ul>
        </div>
        </div>
    </footer>
  </div>
</template>

<script>
export default {
    name: 'app-footer'
}
</script>

<style scoped>
li a{
    color: rgb(185, 182, 182);
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