<script setup>
import HomeCarousel from '@/components/HomeCarousel.vue';
</script>

<template>
  <div class="container-fluid bg-primary border-bottom border-secondary border-4 mb-5">
    <nav class="navbar navbar-expand-lg bg-primary">
      <div class="container-fluid">
        <a class="navbar-brand text-white" href="#">FESTIVA</a>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarNav"
          aria-controls="navbarNav"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav">
            <li class="nav-item">
              <a class="nav-link custom-link" aria-current="page" href="#">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link custom-link" href="#">Features</a>
            </li>
            <li class="nav-item">
              <a class="nav-link custom-link" href="#">Pricing</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </div>

  <div class="container">
    <div class="row gy-5">
      <div class="col-lg-5 text-center">
        <h1>FESTIVA</h1>
        <p>
          Looking to throw an epic festival but don't know where to start? Look no further than
          Festiva! We're the ultimate party planners, helping you create the most awesome,
          mind-blowing, and unforgettable festivals around. 😎
        </p>
        <p>
          Plus, with our lively community of festival enthusiasts, you'll never run out of ideas or
          inspiration. So come on, join the Festiva family and let's create some unforgettable
          memories together!
        </p>
        <button class="btn btn-primary text-white">Join the Community</button>
      </div>
      <div class="col-lg-7">
        <HomeCarousel />
      </div>
    </div>
  </div>
</template>

<style scoped lang="scss"></style>
