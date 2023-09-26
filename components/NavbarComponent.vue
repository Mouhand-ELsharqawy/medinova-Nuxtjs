<template>
  <div class="container-fluid sticky-top bg-white shadow-sm">
        <div class="container">
            <nav class="navbar navbar-expand-lg bg-white navbar-light py-3 py-lg-0">
                <router-link to ="/" class="navbar-brand">
                    <h1 class="m-0 text-uppercase text-primary"><i class="fa fa-clinic-medical me-2"></i>Medinova</h1>
                </router-link>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarCollapse">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarCollapse">
                    <div class="navbar-nav ms-auto py-0">
                        <router-link to ="/" class="nav-item nav-link">Home</router-link>
                        <router-link to ="/about" class="nav-item nav-link">About</router-link>
                        <router-link to ="/service" class="nav-item nav-link">Service</router-link>
                        <router-link to ="/price" class="nav-item nav-link">Pricing</router-link>
                    
                              <router-link to ="/blog" class="nav-link">Blog Grid</router-link>
                              <router-link to ="/detail" class="nav-link">Blog Detail</router-link>
                              <router-link to ="/team" class="nav-link">The Team</router-link>
                              <router-link to ="/testimonial" class="nav-link">Testimonial</router-link>
                              <router-link to ="/appointment" class="nav-link">Appointment</router-link>
                              <router-link to ="/search" class="nav-link">Search</router-link>
                       
                        
                        <router-link to ="/contact" class="nav-item nav-link">Contact</router-link>
                    </div>
                </div>
            </nav>
        </div>
    </div>

</template>
