<template>
<section class="productGrid mt-5 ">
    <div class="container">

        <div class="row">
            <h3 class="my-4">Trending Product</h3>
            <div class="col-lg-4">
                <div class="card" style="width: 18rem;">
                    <img :src="product1" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">Gonher Command M-118 Shot Gun</h5>
                        <p class="card-text">
                            <del class="text-secondary">$45.00</del>
                            $40.00
                        </p>
                        <a href="#" class="btn btn-dark px-5 py-2">View</a>
                    </div>
                </div>
            </div>
            <div class="col-lg-4">
                <div class="card" style="width: 18rem;">
                    <img :src="product2" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title text-sm">We smg8 gas blowback smg (tan) Extreme Airsoft</h5>
                        <p class="card-text">
                            <del class="text-secondary">$22.00</del>
                            $20.00
                        </p>
                         <a href="#" class="btn btn-dark px-5 py-2">View</a>
                    </div>
                </div>
            </div>
            <div class="col-lg-4">
                <div class="card" style="width: 18rem;">
                    <img :src="product3" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">KWC PT92 Gas Gun-Mi7 Security Hyperstore</h5>
                        <p class="card-text">
                            <del class="text-secondary">$45.00</del>
                            $40.00
                        </p>
                        <a href="#" class="btn btn-dark px-5 py-2">View</a>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>
</template>
<script setup>
import product1 from '@/assets/images/244.webp';
import product2 from '@/assets/images/24.webp';
import product3 from '@/assets/images/244.webp';
</script>
<style scoped>
.row{
    padding-left: 200px;
    padding-right: 200px;
}
</style>
