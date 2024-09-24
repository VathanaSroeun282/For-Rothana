<template>
    <div class="w-48">
        <!-- cart -->
        <div class="bg-slate-500 flex justify-center items-center pb-4 pt-6 rounded-md">
            <!-- cart layout -->
            <div>
                <!-- cart logo -->
                <div>
                    <img src="./../../../assets/Img ICON/dell logo.png" class="w-6 ml-3" alt="dell logo">
                </div>
                <!-- cart Img -->
                <div>
                    <img src="./../../../assets/Img ICON/pc1.avif" class="w-40" alt="dell pc1">
                </div>
                <!-- cart description -->
                <div class="pt-4">
                    <!-- cart title -->
                    <div class="flex justify-between items-center">
                        <h3 class="font-bold">Dell Vestre</h3>
                        <button @click="taggleIcon" ><img :src="myIcon" alt="img" class="w-6"></button>
                    </div>
                    <!-- cart model -->
                    <h4>Dis Dell Vestre</h4>
                    <!-- cart price -->
                    <p class="pb-4">
                        <span>1000$</span>
                        <span class="text-red-600 px-4">10%</span>
                        <span class="text-green-600">900$</span>
                    </p>
                    <div>
                        <button class="px-2 py-1 bg-blue-400 rounded-md font-bold text-white">Add to Cart</button>
                    </div>
                </div>
            </div>
        </div>    
    </div>
</template>
<script setup>
import { ref } from 'vue';
import icon1 from './../../../assets/Img ICON/heart fill.png';
import icon2 from './../../../assets/Img ICON/heart.png';

    const myIcon = ref(icon1);
    const taggleIcon = ()=>{
        myIcon.value = myIcon.value === icon1 ? icon2 : icon1;
    }
</script>