<template>
    <div class="bg-secondary  py-[80px]  ">
        <div class="max-w-[1440px] mx-auto grid gap-[20px] grid-cols-1 lg:grid-cols-2">
            <div>
                
                <img class="w-full h-full object_fit" src="/img/map.png" />
            </div>
            <div class="flex flex-col gap-[20px] px-[20px]">
                <h1 class="text-white text-[40px] font-[600]">Our Solutions</h1>
                <div class="grid grid-cols-1 md:grid-cols-2 gap-[20px] text-gray-200">
                    <div class="gradient_bg flex flex-col gap-[5px]">
                        <div class="bg-white flex items-center justify-center text-secondary py-[15px] px-[20px] rounded-tr-xl  rounded-bl-xl  w-fit">
                            <span><i class="pi pi-sync font-bold "></i></span>
                        </div>
                        <h1 class="text-[25px] font-bold">Photovoltaic inverters</h1>
                        <p class="text-[15px] text-justify">Inverters can generate massive amounts of heat and need to operate reliably in harsh outdoor environments. Without proper shelter and preservation from the elements, they are at great risk of damage</p>
                    </div>
                    <div class="gradient_bg flex flex-col gap-[5px]">
                        <div class="bg-white flex items-center justify-center text-secondary py-[15px] px-[20px] rounded-tr-xl  rounded-bl-xl  w-fit">
                            <span><i class="pi pi-th-large font-bold "></i></span>
                        </div>
                        <h1 class="text-[25px] font-bold">Solar Power</h1>
                        <p class="text-[15px] text-justify">Solar power, often referred to as solar energy, is a sustainable and renewable source of electricity harnessed from the sun's radiation. It has emerged as a promising solution to address the world's growing energy needs while mitigating the adverse effects of climate change</p>
                    </div>
                    <div class="gradient_bg flex flex-col gap-[5px]">
                        <div class="bg-white flex items-center justify-center text-secondary py-[15px] px-[20px] rounded-tr-xl  rounded-bl-xl  w-fit">
                            <span><i class="pi pi-bolt font-bold "></i></span>
                        </div>
                        <h1 class="text-[25px] font-bold">Energy Storage</h1>
                        <p class="text-[15px] text-justify">Scalable, efficient and reliable energy storage is key to the global energy transition toward renewables. It is critical for keeping energy sources functioning even after the sun goes down or the wind stops</p>
                    </div>
                   
                    
                </div>
            </div>
            
        </div>
    </div>
</template>

<style scoped>
    .object_fit{
        object-fit:cover;
    }
</style>
