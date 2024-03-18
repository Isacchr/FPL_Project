<script setup>
import Grey_shirt from "../assets/images/Grey_shirt.png"
</script>   

<script>
    export default {
    data() {
        return {
        GreyShirt: Grey_shirt
        };
    },
    methods: {},
    };
</script>

<template>
    <div class="bg-white w-[90%] h-[80%] m-auto opacity-85 rounded-md">

        <div class="h-full">

            <div class="w-full h-[20%]">

            </div>

            <div class="flex justify-center">        
                <img :src="GreyShirt" class="w-[15%] h-auto laptop:w-[10%] xl:w-[5%]">
            </div> 


            <div class="flex justify-evenly">        
                <img :src="GreyShirt" class="w-[15%] h-auto laptop:w-[10%] xl:w-[5%]">
                <img :src="GreyShirt" class="w-[15%] h-auto laptop:w-[10%] xl:w-[5%]">
                <img :src="GreyShirt" class="w-[15%] h-auto laptop:w-[10%] xl:w-[5%]">
                <img :src="GreyShirt" class="w-[15%] h-auto laptop:w-[10%] xl:w-[5%]">
            </div> 

            <div class="flex justify-evenly md:bg-red-700 xl:bg-green-700">        
                <img :src="GreyShirt" class="w-[15%] h-auto laptop:w-[10%] xl:w-[5%]">
                <img :src="GreyShirt" class="w-[15%] h-auto laptop:w-[10%] xl:w-[5%]">
                <img :src="GreyShirt" class="w-[15%] h-auto laptop:w-[10%] xl:w-[5%]">
                <img :src="GreyShirt" class="w-[15%] h-auto laptop:w-[10%] xl:w-[5%]">
            </div> 

            <div class="flex justify-evenly">         
                <img :src="GreyShirt" class="w-[15%] h-auto xl:w-[5%] laptop:w-[10%]">
                <img :src="GreyShirt" class="w-[15%] h-auto xl:w-[5%] laptop:w-[10%]">
            </div> 

        </div>

    </div>
</template>
