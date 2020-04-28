<template>
    <div class="bg-dark text-white py-3">
        <footer class="container">
            <div class="row">
                <!-- <div class="col-12 col-md">
                    <img class="mb-2" src="https://cdn.pixabay.com/photo/2017/01/31/23/42/animal-2028258_960_720.png" alt="" width="50">
                    <small class="d-block text-white">&copy; XYZ company 2017-2019</small>
                </div> -->
                <div class="col-6 col-md">
                    <h5>Resources</h5>
                    <ul class="list-unstyled text-small">
                    <li><a href="#">Home</a></li>
                    <li><a href="#">About</a></li>
                    <li><a href="#">Blog</a></li>
                    <li><a href="#">Contact</a></li>
                    </ul>
                </div>
                <div class="col-6 col-md">
                    <h5>Company</h5>
                    <ul class="list-unstyled text-small">
                    <li><a href="#">Product</a></li>
                    <li><a href="#">FAQ</a></li>
                    <li><a href="#">Privacy Policy</a></li>
                    <li><a href="#">Terms & Conditions</a></li>
                    </ul>
                </div>
                <div class="col-6 col-md">
                    <h5>Contact Details</h5>
                    <ul class="list-unstyled text-small">
                    <li><i class="fa fa-map-marker" aria-hidden="true"></i>221B Baker Street</li>
                    <li><i class="fa fa-phone" aria-hidden="true"></i>(372) 587-2335</li>
                    <li><i class="fa fa-clock-o" aria-hidden="true"></i>11 a.m - 12 p.m</li>
                    </ul>
                </div>

                <div class="pl-3">
                    <h5>Sign up for Newsletter</h5>
                    <div class="input-group mb-3">
                        <input type="text" class="form-control" placeholder="Enter Email Address" aria-label="Recipient's username" aria-describedby="basic-addon2">
                        <div class="input-group-append">
                            <button class="btn btn-secondary" type="button" style="background: #7a77d0;"><span class="fa fa-paper-plane pr-1" aria-hidden="true"></span></button>
                        </div>
                    </div>
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
i{
    padding-right: 10px;
}
li a{
    color: rgb(185, 182, 182);
}
</style>