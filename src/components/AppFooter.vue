<template>
    <div class="appfooter pb-2">
        <footer class="container py-5">
            <div class="row">
                <!-- <div class="col-12 col-md">
                    <img class="mb-2" src="https://cdn.pixabay.com/photo/2017/01/31/23/42/animal-2028258_960_720.png" alt="" width="50">
                    <small class="d-block text-white">&copy; XYZ company 2017-2019</small>
                </div> -->
                <div class="col-6 col-md">
                    <h6>Resources</h6>
                    <ul class="list-unstyled text-small">
                    <li><a href="#">Home</a></li>
                    <li><a href="#">About</a></li>
                    <li><a href="#">Blog</a></li>
                    <li><a href="#">Contact</a></li>
                    </ul>
                </div>
                <div class="col-6 col-md">
                    <h6>Company</h6>
                    <ul class="list-unstyled text-small">
                    <li><a href="#">Product</a></li>
                    <li><a href="#">FAQ</a></li>
                    <li><a href="#">Privacy Policy</a></li>
                    <li><a href="#">Terms & Conditions</a></li>
                    </ul>
                </div>
                <div class="col-6 col-md">
                    <h6>Contact Details</h6>
                    <ul class="list-unstyled text-small">
                    <li><i class="fa fa-map-marker" aria-hidden="true"></i>221B Baker Street</li>
                    <li><i class="fa fa-phone" aria-hidden="true"></i>(372) 587-2335</li>
                    <li><i class="fa fa-clock-o" aria-hidden="true"></i>11 a.m - 12 p.m</li>
                    </ul>
                </div>

                <div class="pl-3">
                    <h6>Sign up for Newsletter</h6>
                    <div class="input-group mt-3">
                        <input type="text" class="form-control" placeholder="Enter Email Address" aria-label="Recipient's username" aria-describedby="basic-addon2">
                        <div class="input-group-append">
                            <button class="btn btn-secondary" type="button" style="background: #7a77d0;"><span class="fa fa-paper-plane pr-1" aria-hidden="true"></span></button>
                        </div>
                    </div>
                </div>
            </div>
    </footer>
    <div class="footer-end text-center">
        <p>© Built with pride and caffeine. All rights reserved.</p>    
    </div>    
  </div>
</template>

<script>
export default {
    name: 'app-footer'
}
</script>

<style lang="scss" scoped>
h6{
    color: gray;
}
.appfooter{
    line-height: 2em;
    background: #141414;
}
.footer-end{
    border-top: 1px solid rgba(83, 81, 81, 0.63);
    p{
        color: gray;
        padding-top: 10px;
        font-size: 13px;
    }
}
i{
    padding-right: 10px;
}
li, li a{
    font-size: 13px;
    color: rgb(212, 207, 207);
}
</style>