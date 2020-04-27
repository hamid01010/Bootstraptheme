<template>
  <div class="email-section">
    <div class="container">
        <div class="row">
            <div class="col-md-6">
                <div class="img">
                    <img class='img-fluid' src="http://webify-13e95.kxcdn.com/demo/webify/creative/wp-content/uploads/sites/8/2019/04/newsletter-img.png">
                </div>
            </div>
            <div class="col-md-6">
                <div class="Email my-3 pl-2">
                    <h1>Get updates at your inbox, Whenever you want it.</h1>
                    <p>News and updates of our product, people & more</p>
                        <div class="input-group mb-3">
                            <input type="email" class="form-control" placeholder="Email Address" aria-label="Recipient's username" aria-describedby="basic-addon2">
                            <div class="input-group-append">
                                <button class="btn btn-success" type="button">Subscribe Newsletter</button>
                            </div>
                    </div>  
                </div>
            </div>
        </div>
    </div>
</div>
</template>

<script>
export default {
    name: "email-section"
}
</script>

<style scoped>
img{
    padding-left: 60px;
}
.email-section{
    background: #7a77d0;
    padding: 50px 0
}
h1, p{
    color: white;
}

</style>