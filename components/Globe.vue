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
                        <h1 class="text-[25px] font-bold">Waste-to-Energy</h1>
                        <p class="text-[15px] text-justify">Lorem ipsum dolor sit amet consectetur adipisicing elit. Fugiat magni, eaque quisquam temporibus dolore porro qui</p>
                    </div>
                    <div class="gradient_bg flex flex-col gap-[5px]">
                        <div class="bg-white flex items-center justify-center text-secondary py-[15px] px-[20px] rounded-tr-xl  rounded-bl-xl  w-fit">
                            <span><i class="pi pi-th-large font-bold "></i></span>
                        </div>
                        <h1 class="text-[25px] font-bold">Solar Power</h1>
                        <p class="text-[15px] text-justify">Lorem ipsum dolor sit amet consectetur adipisicing elit. Fugiat magni, eaque quisquam temporibus dolore porro qui</p>
                    </div>
                    <div class="gradient_bg flex flex-col gap-[5px]">
                        <div class="bg-white flex items-center justify-center text-secondary py-[15px] px-[20px] rounded-tr-xl  rounded-bl-xl  w-fit">
                            <span><i class="pi pi-bolt font-bold "></i></span>
                        </div>
                        <h1 class="text-[25px] font-bold">Energy Storage</h1>
                        <p class="text-[15px] text-justify">Lorem ipsum dolor sit amet consectetur adipisicing elit. Fugiat magni, eaque quisquam temporibus dolore porro quia autem. </p>
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