<script setup>
import Navigation from '@/components/Navigation.vue';
import ProductDetail from '@/components/ProductDetail.vue';
import ProductGrid from '@/components/ProductGrid.vue';
import TopBar from '@/components/TopBar.vue';
</script>

    <template>
  <div class="header-container position-relative">
    <TopBar />
    <Navigation />
    <ProductGrid />
    <ProductDetail />
    </div>
 
</template>

<style scoped>
/* Ensures proper positioning */
.header-container {
  position: relative;
  z-index: 10;
}
</style>
