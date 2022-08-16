<template>
  <div class="min-h-screen -mt-[80px] pt-[80px] px-5 xl:px-0 bg-Grayscale relative">
    <div class="grid xl:grid-cols-2">
      <div class="xl:px-[120px] xl:py-20 container z-10">
        <h1 class="font-semibold text-6xl lg:text-7xl text-white lg:leading-[80px]">
          Get your dream body with us at
          <span class="text-transparent bg-clip-text bg-gradient-to-r from-Primary to-Primary2">Fitness</span>
        </h1>
        <p class="pt-10 text-Secondary text-base">
          Fitness help you to create an environment that supports your program to live a healthy life, and get a beautiful
body shape
        </p>
        <div class="my-10 flex gap-4">
          <a href="#" class="duration-300 border rounded px-12 py-3 text-white border-transparent bg-gradient-to-tr from-Primary to-Primary2 cursor-pointer hover:scale-110">Get Started</a>
          <a href="#" class="rounded px-5 text-white flex items-center gap-3 hover:text-transparent hover:bg-clip-text hover:bg-gradient-to-tr hover:from-Primary hover:to-Primary2 hover:scale-110 duration-300">
            <img :src="PlayButtonGradient" class="w-8" alt="">
            <span class="font-semibold underline">How It Works?</span>
          </a>
        </div>
      </div>
      <div class="xl:relative hidden xl:inline">
        <img :src="Model1" class="xl:absolute xl:right-0 top-0 bottom-0 z-20" alt="">
        <img :src="CircleBg" class="xl:absolute xl:top-0 right-32 z-10" alt="">
        <!-- GymIcon -->
        <div class="flex p-1 rounded-lg w-10 h-10 absolute md:bottom-[25%] lg:right-44 rotate-12 z-20 bg-gradient-to-tl from-Coral to-Lavender">
          <img :src="GymIcon"/>
        </div>
        <!-- Box Youtube -->
        <div class="p-1 rounded-lg w-44 h-20 absolute z-20 bg-gradient-to-l from-[#3A3A3A4D]/50 to-[#DEDEDE]/50 border border-transparent flex justify-center align-middle items-center gap-5 top-[45%] left-[15%]">
          <img :src="YoutubeIcon"/>
          <div>
            <h6 class="font-bold text-3xl text-white">250+</h6>
            <p class="font-normal text-xs text-white">Tutorial Video</p>
          </div>
        </div>
        <div class="p-3 rounded-lg w-44 h-20 absolute z-20 bg-gradient-to-l from-[#3A3A3A4D]/50 to-[#DEDEDE]/50 border border-transparent flex-col justify-center align-middle items-center content-center gap-5 top-[5%] right-[25%] -space-x-2">
            <div class="">
              <img class="inline-block h-7 w-7 rounded-full ring-2 ring-white" :src="People" alt=""/>
              <img class="inline-block h-7 w-7 rounded-full ring-2 ring-white" :src="People1" alt=""/>
              <img class="inline-block h-7 w-7 rounded-full ring-2 ring-white" :src="People2" alt=""/>
              <span class="font-semibold text-2xl text-white ml-2">+15K</span>
            </div>
            <p class="pl-2 text-xs pt-2 text-white">User already join us.</p>
        </div>
      </div>
    </div>
    <div class="hidden xl:inline absolute top-0 z-0 bg-gradient-to-tl from-Grayscale via-Grayscale to-Primary2/10 h-[700px] w-[700px]"></div>
    <div class="absolute bottom-0 right-0 -z-1 bg-gradient-to-br from-Grayscale via-Grayscale to-Primary2/10 h-[700px] w-[700px]"></div>
  </div>
</template>

<script setup>
import Model1 from '@images/Model1.svg'
import CircleBg from '@images/Circle_Background.png'
import PlayButtonGradient from '@images/PlayButtonGradient.png'
import GymIcon from '@images/gym.png'
import YoutubeIcon from '@images/Youtube.png'
import People from '@images/People.png'
import People1 from '@images/People1.png'
import People2 from '@images/People2.png'

console.log(Model1)
</script>

<style>

</style>