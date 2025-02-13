<template>
<section class="wrapper bg-body-secondary">
<div class="container-fluid">
    <div class="row mt-5">
       
        <div class="col-lg-6 p-0 text-lg-end">
            <img :src="product1" class="img1" alt="img" width="450px"height="auto">
        </div>
        <div class="col-lg-6 pt-5 px-5 ">
            <span class="text-secondary ">AR15 Gen 2</span>
            <h3 class="my-3">Top Product Categories</h3>
            <p class="text-secondary w-75">
                Our AR15 Gen 2 Stripped Lower Receiver is the perfect base for your custom AR15 build.
                Machined to mil-sec dimensions our lowers work with standard AR15 components and Ensures
                the highest quality with a correct components interface.
                        </p>
                        <img :src="product2" alt="img" width="200px"height="auto">
                    </div>
    </div>
</div>
</section>
</template>
<script setup>
import product1 from '@/assets/images/AR15_Blade_1-1024x853.webp';
import product2 from '@/assets/images/Blade_1_Lineart.webp';

</script>
<style scoped>
.img1{
    border: solid 10px white;
}
</style>