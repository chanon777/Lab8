<script setup>

import { useRoute } from 'vue-router';

const route = useRoute()
const id = parseInt(route.params.id)

</script>
<template>
 <div class="row mb-2">
    <div class="col-md-6" >
      <div class="row g-0 border rounded overflow-hidden flex-md-row mb-4 shadow-sm h-md-250 position-relative">
        <div class="col p-4 d-flex flex-column position-static">
        
          
          <h3 class="mb-0">{{ id }}.  TOYOTA SUPAR MK5 2020 </h3>
         
          <p >
              <img src="https://cf.autodeft2.pw/uploads/images/2023-Toyota-Supra-2.jpg" width=500 href="#">

            </p>
          <p class="card-text mb-auto">
            <h3 class="mb-0">5,199,000 </h3>
          

            ติดต่อเซลขายรถ <br>

            tel.06x xxx xxxx <br>

            ยังไม่มีคะแนน (0 รีวิว) 
        </p>
        

            <div class="col-4 ">
            <a class="link-secondary" href="#" aria-label="Search">
            <svg xmlns="http://www.w3.org/2000/svg" width="5" height="5" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="mx-3" role="img" viewBox="0 0 24 24"><title>Search</title><circle cx="10.5" cy="10.5" r="7.5"/><path d="M21 21l-5.2-5.2"/></svg>
            </a>
          </div>
        </div>
        <div class="col-auto d-none d-lg-block">
          
        </div>
      </div>
    </div>
 </div>
</template>
