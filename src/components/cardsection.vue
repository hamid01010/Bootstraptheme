<template>
    <div class="container mt-5">
        <div class="cards mt-3">

            <div class="row">
                <div class="col-sm-6 mt-4 firstone">
                    <div class="card">
                    <div class="card-body">
                        <h5 class="card-title">Special title treatment</h5>
                        <p class="card-text">With supporting text below as a natural lead-in to additional content.
                        <a href="#" class="text-white"><b>Read more</b></a></p>
                    </div>
                    </div>
                </div>
                <div class="col-sm-6">
                    <div class="card">
                        <div class="card-body">
                            <h5 class="card-title">Special title treatment</h5>
                            <p class="card-text">With supporting text below as a natural lead-in to additional content.
                            <a href="#" class="text-white"><b>Read more</b></a></p>
                        </div>
                    </div>
                </div>
            </div>

            <div class="row">
            <div class="col-sm-6 mt-4 firstone">
                <div class="card">
                <div class="card-body">
                    <h5 class="card-title">Special title treatment</h5>
                    <p class="card-text">With supporting text below as a natural lead-in to additional content.
                    <a href="#" class="text-white"><b>Read more</b></a></p>
                </div>
                </div>
            </div>
            <div class="col-sm-6">
                <div class="card">
                <div class="card-body">
                    <h5 class="card-title">Special title treatment</h5>
                    <p class="card-text">With supporting text below as a natural lead-in to additional content.
                    <a href="#" class="text-white"><b>Read more</b></a></p>
                </div>
                </div>
            </div>
            </div>
        
        </div>
        <div class="sidebar">
            <h1>Lorem ipsum dolor sit amet consectetur</h1>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Atque sunt nam, ipsam tempora ea neque temporibus laborum! Ipsam sapiente ab veniam perferendis voluptas, quia ratione rem velit iure placeat quo. Lorem ipsum dolor sit amet consectetur adipisicing elit. Eaque nihil deserunt ab, laboriosam error illum sed ad, ratione fugit autem voluptatum earum tenetur quam alias accusantium quos enim expedita labore!</p>
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

<style lang="scss" scoped>
p{
    color:gray
}
.card:hover{
    background: #3bb0f5;
    color: white;
    p{
        color:white
    }
    
    a{
        display: inline;
    }    
}
.card a{
    display: none;
}
.cards{
    float: left;
    width: 50%;
    box-sizing: border-box;
}
.sidebar{
    padding: 50px 20px 50px 50px;
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
    .firstone{
        margin-bottom: 20px;
    }
}
.clr{
	clear:both;
}

</style>