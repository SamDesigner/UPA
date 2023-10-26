<template>
    <div class=w-full>
        <div class="navbar px-[16px] md:px-0  py-[10px] w-auto mx-auto shadow-lg   " :class="{ 'opaque': isNavbarOpaque }">
          
          <nav class=" mx-auto max-w-[1440px] md:px-[20px] lg:px-[80px] flex justify-between items-center ">
              <nuxt-link to="/"  >
                  <img class="h-[50px] " src="/img/logo.png" />
              </nuxt-link>
              
              <div class="hidden md:flex items-center space-x-8 ">
                  <nuxt-link to="/">Home</nuxt-link>
                  <nuxt-link to="/about">About us</nuxt-link>
                  <nuxt-link to="/services">Services</nuxt-link>
                  <nuxt-link to="/candidates">Candidates</nuxt-link>
                  <nuxt-link to="/contact">Contact us</nuxt-link>
              </div>
              <div class="hidden lg:flex" >
                  <nuxt-link to="/contact">
                      <div class=" bg-primary  text-white py-3 px-6 rounded-3xl flex items-center gap-3 ">
                          <span>Book an appointment</span>
                          <i class="pi pi-arrow-right text-xs"></i>
                      </div>
                  </nuxt-link>
                 
              </div>
              <div class="block md:hidden"  @click="handleIsOpen">
                      <span><i class="pi pi-bars text-xl text-primary"></i></span>
              </div>
          </nav>
          
      </div>
    </div>
</template>


<script>
    export default{
        data() {
            return {
            isNavbarOpaque: false,
            };
        },
        mounted() {
            window.addEventListener('scroll', this.handleScroll);
        },
        beforeDestroy() {
            window.removeEventListener('scroll', this.handleScroll);
        },
        methods: {
            handleScroll() {
            const scrollY = window.scrollY;

            // Define a specific scroll position where the navbar becomes opaque
            const scrollTrigger = 100; // Adjust this value as needed

            if (scrollY >= scrollTrigger) {
                this.isNavbarOpaque = true;
            } else {
                this.isNavbarOpaque = false;
            }
            },
        },
       
    }
</script>
<style scoped>
     .navbar {
        position: fixed;
        top: 0;
        left: 0;
        width: 100%;
        padding: 20px;
        background: transparent;
        transition: background 0.3s ease; /* Add a smooth transition effect */
        z-index: 1000;
        color: white !important;
     }
     .opaque {
        background: white; /* Change the background color to white */
        color: black !important;
    }
    .router-link-exact-active{
        color:#00662A; 
    }

</style>