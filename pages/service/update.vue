<template>
  <div class="col-lg-6">
                     <div class="bg-light text-center rounded p-5">
                         <h1 class="mb-4">Update service </h1>
                         <form @submit.prevent="handleSubmit">
                             <div class="row g-3">
                                 <div class="col-12 col-sm-6">
                                     <input type="text" 
                                     class="form-control bg-white border-0" 
                                     placeholder="Service Title" 
                                     style="height: 55px;"
                                     v-model="title">
                                 </div>
                                 <div class="col-12 col-sm-6">
                                     <input type="text" 
                                     class="form-control bg-white border-0" 
                                     placeholder="Service Description" 
                                     style="height: 55px;"
                                     v-model="body">
                                 </div>
                                 
                                 <div class="col-12">
                                     <button class="btn btn-primary w-100 py-3" type="submit">Make An Appointment</button>
                                 </div>
                             </div>
                         </form>
                     </div>
                 </div>
</template>

<script setup>
definePageMeta({
    layout: 'default'
})
</script>

<style>

</style>