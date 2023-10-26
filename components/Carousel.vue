
<template>
    <div class="bg-grayBg ">
    <div >
    
       
            <div class="h-[100vh] ">
                <swiper
                    class="h-full"
                    :modules="modules"
                    :slides-per-view="1"
                    :loop="true"
                    :autoplay="{
                    delay: 4000,
                    disableOnInteraction: true,
                    }"
                    :pagination="{ clickable: true }"
                    @swiper="onSwiper"
                    @slideChange="onSlideChange"
                   
                >
                    <swiper-slide>
                       <div class="h-[100%] bg_2 px-[16px] md:px-[40px] lg:px-[80px]">
                            <div class="h-full w-full flex justify-center items-center md:justify-start">
                                <div class="text-white  md:w-[600px] flex flex-col gap-[20px]">
                                    <h1 class="text-[24px] md:text-[50px] font-[700]">Empowering Nigeria through Innovative Energy Solutions</h1>
                                    <p class="font-[100] leading-[25px]">Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestias id harum eos atque, facere laboriosam esse cumque officiis sunt optio maiores?</p>
                                    <div class="md:pt-[30px] flex gap-x-[30px]">
                                        <Nuxt-link class="border border-white px-[30px] text-[14px] rounded-3xl hover:bg-white hover:text-black pointer font-[300] py-[15px]">Get Started</Nuxt-link>
                                        <Nuxt-link class="border border-white px-[30px] text-[14px] rounded-3xl hover:bg-white hover:text-black pointer font-[300] py-[15px]">Our Services</Nuxt-link>
                                    </div>
                                </div>

                            </div>
                       </div>
                    </swiper-slide>
                    <swiper-slide>
                       <div class="h-[100%] bg_3 px-[16px] md:px-[40px] lg:px-[80px]">
                        <div class="h-full w-full flex justify-center items-center md:justify-start">
                                <div class="text-white  md:w-[600px] flex flex-col gap-[20px]">
                                    <h1 class="text-[24px] md:text-[50px] font-[700]">Empowering Nigeria through Innovative Energy Solutions</h1>
                                    <p class="font-[100] leading-[25px]">Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestias id harum eos atque, facere laboriosam esse cumque officiis sunt optio maiores?</p>
                                    <div class="md:pt-[30px] flex gap-x-[30px]">
                                        <Nuxt-link class="border border-white px-[30px] text-[14px] rounded-3xl hover:bg-white hover:text-black pointer font-[300] py-[15px]">Get Started</Nuxt-link>
                                        <Nuxt-link class="border border-white px-[30px] text-[14px] rounded-3xl hover:bg-white hover:text-black pointer font-[300] py-[15px]">Our Services</Nuxt-link>
                                    </div>
                                </div>

                            </div>
                       </div>
                    </swiper-slide>
                    <swiper-slide>
                       <div class="h-[100%] bg_1 px-[16px] md:px-[40px] lg:px-[80px]">
                        <div class="h-full w-full flex justify-center items-center md:justify-start">
                                <div class="text-white  md:w-[600px] flex flex-col gap-[20px]">
                                    <h1 class="text-[24px] md:text-[50px] font-[700]">Empowering Nigeria through Innovative Energy Solutions</h1>
                                    <p class="font-[100] leading-[25px]">Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestias id harum eos atque, facere laboriosam esse cumque officiis sunt optio maiores?</p>
                                    <div class="md:pt-[30px] flex gap-x-[30px]">
                                        <Nuxt-link class="border border-white px-[30px] text-[14px] rounded-3xl hover:bg-white hover:text-black pointer font-[300] py-[15px]">Get Started</Nuxt-link>
                                        <Nuxt-link class="border border-white px-[30px] text-[14px] rounded-3xl hover:bg-white hover:text-black pointer font-[300] py-[15px]">Our Services</Nuxt-link>
                                    </div>
                                </div>

                            </div>
                       </div>
                    </swiper-slide>
                   
                 
                
                

                   


            </swiper>        
                
            </div>
        </div>
       
    </div>
</template>
<style scoped>
    .carousel_img{
        object-fit:cover ;
    }
 
    
    .bg_1{
        background:linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.8)) ,url('/img/solardawn.jpg');
        background-position:top;
        background-size:cover
    }   
    .bg_2{
        background:linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.8)) , url('/img/solarteam.jpg');
        background-position:center;
        background-size:cover
    }   
    .bg_3{
        background:linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.8)) , url('/img/solarpanel.jpg');
        background-position:center;
        background-size:cover
    }   
</style>
<script>
   import { Navigation, Pagination, Scrollbar, A11y, Autoplay } from 'swiper/modules';

    // Import Swiper Vue.js components
    import { Swiper, SwiperSlide } from 'swiper/vue';

    // Import Swiper styles
    import 'swiper/css';
    import 'swiper/css/navigation';
    import 'swiper/css/pagination';
    import 'swiper/css/scrollbar';

    // Import Swiper styles
    export default {
    components: {
        Swiper,
        SwiperSlide,
    },
    setup() {
        const onSwiper = (swiper) => {
        console.log(swiper);
        };
        const onSlideChange = () => {
        console.log('slide change');
        };
        return {
        onSwiper,
        onSlideChange,
        modules: [Navigation, Pagination, Scrollbar, A11y , Autoplay ,],
        };
    },
    };
</script>
