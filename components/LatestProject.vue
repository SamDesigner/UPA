<template>
    <div class="bg-grayBg py-[80px] px-[16px]">
            <div class="max-w-[1440px] mx-auto space-y-4 md:space-y-0 grid grid-cols-1 md:grid-cols-2 items-center">
                <div class="flex flex-col gap-[12px]">
                    <h3 class="text-primary">Innovation, Quality and Continous Improvement</h3>
                    <h1 class="text-darkYellow text-[28px] lg:text-[45px] font-[600px]">Latest Project, Solutions And Energy Supplies</h1>
                </div>
                <div class="flex flex-col gap-[16px]">
                    <p class="text-gray-500 text-[16px] md:text-[18px] leading-[28px] text-darkYellow">Our sales offices and warehouses include PV industry experience enables us to provide in-depth material sourcing and supply chain expertise for every production & installation process.</p>
                    <button class="bg-primary text-white w-fit py-[20px] px-[25px]">Explore All Projects <span><i class="pi pi-arrow-right"></i></span></button>
                </div>
            </div>


            <div class="py-[40px] hidden lg:flex">
                <swiper
                    class="h-full flex "
                    :modules="modules"
                    :slides-per-view="2.5"
                    spaceBetween:20
                    :loop="true"
                    :autoplay="{
                    delay: 4000,
                    disableOnInteraction: true,
                    }"
                 
                    @swiper="onSwiper"
                    @slideChange="onSlideChange"
                   
                >
                    <swiper-slide class="w-[300px] "> 
                        <div class="h-[400px] w-full    ">
                            <img class="overflow-hidden h-full" src="/img/welding.jpg" />
                        </div>
                        <div class="py-[10px]">
                            <h3 class="text-black text-lg font-[400]">Welding Cables</h3>
                            <div class="border w-[30px] border-b-darkYellow"></div>
                            <p class="text-[14px]">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Delectus ducimus quo animi?</p>
                        </div>
                       
                    </swiper-slide>
                    <swiper-slide class="w-[300px] "> 
                        <div class="h-[400px] w-full    ">
                            <img class="overflow-hidden h-full" src="/img/welding.jpg" />
                        </div>
                        <div class="py-[10px]">
                            <h3 class="text-black text-lg font-[400]">Welding Cables</h3>
                            <div class="border w-[30px] border-b-darkYellow"></div>
                            <p class="text-[14px]">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Delectus ducimus quo animi?</p>
                        </div>
                       
                    </swiper-slide>
                    <swiper-slide class="w-[300px] "> 
                        <div class="h-[400px] w-full    ">
                            <img class="overflow-hidden h-full" src="/img/welding.jpg" />
                        </div>
                        <div class="py-[10px]">
                            <h3 class="text-black text-lg font-[400]">Welding Cables</h3>
                            <div class="border w-[30px] border-b-darkYellow"></div>
                            <p class="text-[14px]">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Delectus ducimus quo animi?</p>
                        </div>
                       
                    </swiper-slide>
                    <swiper-slide class="w-[350px]"> 
                        <div class="h-[400px] w-full    ">
                            <img class="overflow-hidden h-full" src="/img/welding.jpg" />
                        </div>
                        <div class="py-[10px]">
                            <h3 class="text-black text-lg font-[400]">Welding Cables</h3>
                            <div class="border w-[30px] border-b-darkYellow"></div>
                            <p class="text-[14px]">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Delectus ducimus quo animi?</p>
                        </div>
                       
                    </swiper-slide>
                  
                   
                   
                 
                
                

                   


                </swiper>        
              
            </div>
            <div class=" lg:hidden grid md:grid-cols-2 grid-cols-1 gap-[20px] mt-[20px]">
                    <div>
                            <div class="h-[300px] w-full    ">
                                <img class="overflow-hidden rounded-xl h-full" src="/img/welding.jpg" />
                            </div>
                            <div class="py-[10px]">
                                <h3 class="text-black text-lg font-[400]">Welding Cables</h3>
                                <div class="border w-[30px] border-b-darkYellow"></div>
                                <p class="text-[14px]">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Delectus ducimus quo animi?</p>
                            </div>
                    </div>
                    <div>
                            <div class="h-[300px] w-full    ">
                                <img class="overflow-hidden h-full rounded-xl" src="/img/welding.jpg" />
                            </div>
                            <div class="py-[10px]">
                                <h3 class="text-black text-lg font-[400]">Welding Cables</h3>
                                <div class="border w-[30px] border-b-darkYellow"></div>
                                <p class="text-[14px]">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Delectus ducimus quo animi?</p>
                            </div>
                    </div>
                    <div>
                            <div class="h-[300px] w-full    ">
                                <img class="overflow-hidden rounded-xl h-full " src="/img/welding.jpg" />
                            </div>
                            <div class="py-[10px]">
                                <h3 class="text-black text-lg font-[400]">Welding Cables</h3>
                                <div class="border w-[30px] border-b-darkYellow"></div>
                                <p class="text-[14px]">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Delectus ducimus quo animi?</p>
                            </div>
                    </div>
                    <div>
                            <div class="h-[300px] w-full    ">
                                <img class="overflow-hidden rounded-xl h-full" src="/img/welding.jpg" />
                            </div>
                            <div class="py-[10px]">
                                <h3 class="text-black text-lg font-[400]">Welding Cables</h3>
                                <div class="border w-[30px] border-b-darkYellow"></div>
                                <p class="text-[14px]">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Delectus ducimus quo animi?</p>
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
