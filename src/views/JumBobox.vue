<script setup>

</script>
<template>
    <div id="myCarousel" class="carousel " data-bs-ride="carousel">
        <div class="carousel-indicators">
        <button type="button" data-bs-target="#myCarousel" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
        <button type="button" data-bs-target="#myCarousel" data-bs-slide-to="1" aria-label="Slide 2"></button>
        <button type="button" data-bs-target="#myCarousel" data-bs-slide-to="2" aria-label="Slide 3"></button>
        </div>
        <div class="carousel-inner">
        <div class="carousel-item active">
            <img src="../assets/doi1.png" alt="">
        </div>
        <div class="carousel-item">
            <img src="../assets/doi2.png" alt="">
        </div>
        <div class="carousel-item">
            <img src="../assets/doi3.png" alt="">
        </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#myCarousel" data-bs-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#myCarousel" data-bs-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
        </button>
    </div>
</template>


<style scoped>
.carousel {
    width: 100%; 
}
.carousel-item img {
    width: 100%;
    
}
</style>


           