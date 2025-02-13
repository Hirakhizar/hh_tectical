<script setup>
import { RouterLink } from 'vue-router';
import logo from '@/assets/images/23532.webp';
</script>

<template>
  <nav class="navbar navbar-expand-lg bg-white position-relative adjustNav">
    <div class="container position-relative">
      
      <!-- Logo Positioned to Overlap Top Bar -->
      <div class="logo-container">
        <RouterLink to="/">
          <img :src="logo" alt="logo" class="custom-logo">
        </RouterLink>
      </div>

      <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
        data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent"
        aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              Home
            </a>
            <ul class="dropdown-menu">
              <li><a class="dropdown-item" href="#">Action</a></li>
              <li><a class="dropdown-item" href="#">Another action</a></li>
              <li><hr class="dropdown-divider"></li>
              <li><a class="dropdown-item" href="#">Something else here</a></li>
            </ul>
          </li>
          <li class="nav-item"><a class="nav-link" href="#">CheckOut</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Cart</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Shop</a></li>
          <li class="nav-item"><a class="nav-link active" href="#">home 2</a></li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<style scoped>
/* Container to handle positioning */
.logo-container {
  position: absolute;
  top: -50px; /* Moves logo upward to overlap Top Bar */
  left: 20px; /* Adjust as needed */
}

/* Style for the logo */
.custom-logo {
  width: 100px;
  height: auto;
  border-radius: 10px; /* Optional rounded corners */
  
}
.adjustNav{
    padding-left:15%;
    padding-right:15%;
    height: 80px;
    border-bottom: 5px solid #ce2457; /* Pink bottom border */
   
    
}

.navbar-nav .nav-link {
    position: relative;
    padding: 8px 15px; /* Adds spacing */
    transition: all 0.3s ease-in-out;
}

/* Pink Box Hover Effect */
.navbar-nav .nav-link:hover {
    background-color: #ce2457; /* Pink Background */
    color: white !important;  /* Ensures text remains readable */
}
</style>
