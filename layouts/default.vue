<template>
  <TopBarComponent />
  <NavbarComponent />
  <slot />
  <FooterComponent />
</template>

<script setup>
    useHead({
        title: "Medinova"
    })
</script>

<style>
@import url('https://fonts.gstatic.');
@import url('https://fonts.googleapis.com/css2?family=Roboto+Condensed:wght@400;700&family=Roboto:wght@400;700&display=swap');
@import url('https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.0/css/all.min.css');
@import url('https://cdn.jsdelivr.net/npm/bootstrap-icons@1.4.1/font/bootstrap-icons.css');
@import url('../assets/lib/owlcarousel/assets/owl.carousel.min.css');
@import url('../assets/lib/tempusdominus/css/tempusdominus-bootstrap-4.min.css');
@import url('../assets/css/bootstrap.min.css');
@import url('../assets/css/style.css');
a.router-link-exact-active {
  color: #13C5DD;
}
</style>