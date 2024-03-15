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
    <div class="bg-white w-[90%] h-[80%] m-auto text-center opacity-85 rounded-md">
        <p>Yess</p>

        <div class="flex">

        <img :src="GreyShirt" class="w-[8%] h-auto">
        <img :src="GreyShirt" class="w-[8%] h-auto">
        <img :src="GreyShirt" class="w-[8%] h-auto">
        <img :src="GreyShirt" class="w-[8%] h-auto">
        <img :src="GreyShirt" class="w-[8%] h-auto">
        <img :src="GreyShirt" class="w-[8%] h-auto">
        <img :src="GreyShirt" class="w-[8%] h-auto">
        <img :src="GreyShirt" class="w-[8%] h-auto">
        <img :src="GreyShirt" class="w-[8%] h-auto">
        <img :src="GreyShirt" class="w-[8%] h-auto">
        <img :src="GreyShirt" class="w-[8%] h-auto">

        </div>

    </div>
</template>
