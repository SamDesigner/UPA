<template>
    <div class="bg-grayBg py-[80px] px-[16px] flex flex-col gap-[60px]">
            <div class="max-w-[1440px] mx-auto space-y-4 md:space-y-0 grid grid-cols-1 md:grid-cols-2 items-center">
                <div 
                data-aos="fade-right"
                data-aos-easing="linear"
                data-aos-duration="1500"
                class="flex flex-col gap-[12px]">
                    <h3 class="text-primary">Innovation, Quality and Continous Improvement</h3>
                    <h1 class=" text-[28px] lg:text-[45px] font-[600px]">Latest Project, Solutions And Energy Supplies</h1>
                </div>
                <div 
                data-aos="fade-left"
                data-aos-easing="linear"
                data-aos-duration="1500"
                class="flex flex-col gap-[16px]">
                    <p class="text-gray-700 text-[16px] md:text-[18px] leading-[28px] ">Our sales offices and warehouses include PV industry experience enables us to provide in-depth material sourcing and supply chain expertise for every production & installation process.</p>
                    <button class="bg-primary text-white w-fit py-[20px] px-[25px]">Explore All Projects <span><i class="pi pi-arrow-right"></i></span></button>
                </div>
            </div>


          
            <div class=" max-w-[1440px] mx-auto grid md:grid-cols-2 lg:grid-cols-4 grid-cols-1 gap-[30px] mt-[20px]">
                 
                    <div class="">
                            <div class="h-[300px] w-full    ">
                                <img class="overflow-hidden rounded-tr-xl rounded-tl-xl w-full h-full fit_img" src="/img/pic1.jpg" />
                            </div>
                            <div class="py-[10px] bg-white px-[10px] flex flex-col gap-[5px]">
                                <h3 class="text-black text-lg font-[400] text-primary">Solar Batteries</h3>
                                <div class="border w-[30px] border-b-darkYellow"></div>
                                <p class="text-[14px]">Our Solar panels come with in built solar batteries tht will help extend the lifespan of your solar panel</p>
                            </div>
                    </div>
                    <div class="">
                            <div class="h-[300px] w-full    ">
                                <img class="overflow-hidden rounded-tr-xl rounded-tl-xl w-full h-full fit_img" src="/img/pic2.jpg" />
                            </div>
                            <div class="py-[10px] bg-white px-[10px] flex flex-col gap-[5px]">
                                <h3 class="text-black text-lg font-[400] text-primary">Inverters</h3>
                                <div class="border w-[30px] border-b-darkYellow"></div>
                                <p class="text-[14px]">Explore our long lasting inverter batteries, enjoy the quality of the no1 leading brand in nigeria</p>
                            </div>
                    </div>
                    <div class="">
                            <div class="h-[300px] w-full    ">
                                <img class="overflow-hidden rounded-tr-xl rounded-tl-xl w-full h-full fit_img" src="/img/pic3.jpg" />
                            </div>
                            <div class="py-[10px] bg-white px-[10px] flex flex-col gap-[5px]">
                                <h3 class="text-black text-lg font-[400] text-primary">Solar Bulbs</h3>
                                <div class="border w-[30px] border-b-darkYellow"></div>
                                <p class="text-[14px]">Explore our high quality solar bulbs capable of lighting up your domain for 52-hours without any form of glitch </p>
                            </div>
                    </div>
                    <div class="">
                            <div class="h-[300px] w-full    ">
                                <img class="overflow-hidden rounded-tr-xl rounded-tl-xl w-full h-full fit_img" src="/img/pic4.jpg" />
                            </div>
                            <div class="py-[10px] bg-white px-[10px] flex flex-col gap-[5px]">
                                <h3 class="text-black text-lg font-[400] text-primary">Solar Cookers</h3>
                                <div class="border w-[30px] border-b-darkYellow"></div>
                                <p class="text-[14px]">Worried about basic gas, here at upa we break the laws of science, with out top quality solar cooker the first of it's kind </p>
                            </div>
                    </div>
                    <div class="">
                            <div class="h-[300px] w-full    ">
                                <img class="overflow-hidden rounded-tr-xl rounded-tl-xl w-full h-full fit_img" src="/img/pic5.jpg" />
                            </div>
                            <div class="py-[10px] bg-white px-[10px] flex flex-col gap-[5px]">
                                <h3 class="text-black text-lg font-[400] text-primary">Inverter Batteries</h3>
                                <div class="border w-[30px] border-b-darkYellow"></div>
                                <p class="text-[14px]">Our inverter battries are the best in nigeria, purchase one and thank us later.Shop with us now.</p>
                            </div>
                    </div>
                  
                    <div class="">
                            <div class="h-[300px] w-full    ">
                                <img class="overflow-hidden rounded-tr-xl rounded-tl-xl w-full h-full fit_img" src="/img/pic3.jpg" />
                            </div>
                            <div class="py-[10px] bg-white px-[10px] flex flex-col gap-[5px]">
                                <h3 class="text-black text-lg font-[400] text-primary">Solar Smoke Machine</h3>
                                <div class="border w-[30px] border-b-darkYellow"></div>
                                <p class="text-[14px]">Entertainers and influencers can spice up their shows with our solar smoke machine and spice up the event</p>
                            </div>
                    </div>
                    
                
                  
            </div>
        </div>
       
   
</template>

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
            breakpoints: {
                
                320: {
                slidesPerView: 1,
                spaceBetween: 20
                },
                // when window width is >= 480px
                480: {
                slidesPerView: 2,
                spaceBetween: 30
                },
                // when window width is >= 640px
                640: {
                slidesPerView: 3,
                spaceBetween: 40
                }

            },
        onSlideChange,
        modules: [Navigation, Pagination, Scrollbar, A11y , Autoplay ,],
        };
    },
    };
</script>
<style scoped>
    .fit_img{
        object-fit:cover
    }
</style>