<template>
  <div class="w-full bgColor">
    <section class="w-full bgColor">
      <navbar/>
      <!-- Section1 -->
      <div class="container-about mt-20 lg:mt-40 justify-between">
        <div class="lg:flex mx-auto">
          <div class="md:flex-shrink-0 mt-16">
            <p class="introName text-4xl lg:text-4xl text-center lg:text-left">Hi, my name is <span class="firstName">Cody Mullin</span></p>
            <p class="introJob text-2xl lg:text-5xl text-center lg:text-left">I am a front-end web developer <br />& designer</p>
          </div>
          <div class="mt-16 md:mt-8 ml-auto mr-auto h-64 w-64 lg:h-full lg:w-full">
            <img src="../assets/developer.svg" class="float-right p-0 box-sizing:0">
          </div>
        </div>
      </div>
    </section>

    <hr class="mt-8 lg:mt-32">

    <!-- Section2 -->
    <div class="container-about text-center text-white mt-16 lg:mt-24 pl-4 pr-4 md:p-0 mx-auto text-base md:text-2xl ">
      <h1 class="text-5xl text-center pb-8">My Job</h1>
      <p>As a web designer, my job is to help create beautiful websites that are not only amazing to look at, but also have functionality that is easy to maneuver. A website is only as good as its design if a user is able to understand how to traverse the site. My job as a developer is to take these designs and make them come to life. To do this I use tools such as HTML/CSS, VueJS, Tailwind, as well as some others.</p>      </div>      

    <hr class="mt-16 lg:mt-32">

    <!-- Section3 -->
    <div class="container-about text-center text-white mt-16 lg:mt-24 pl-4 pr-4 md:p-0 mx-auto text-base md:text-2xl ">
      <h1 class="text-5xl text-center pb-8">About Me</h1>
      <p>Being that I stay behind a computer for most of the day working on designs and development, I try and stay as active as possible. I enjoy working out, being outside playing disc golf,  and coaching baseball. It is important to me to remain as active as possible, so that I come back with a fresh pair of eyes to determine ways that the project can be improved. This results in better ideas for both the design and functionality of the project. </p>  
    </div>   

    <hr class="mt-16 lg:mt-32">
 
    <!-- Section4 -->
    <div class="container-about text-white text-center mt-16 lg:mt-24 pl-4 pr-4 md:p-0">
      <h1 class="text-5xl text-center pb-8">Skills</h1>
      <div class="flex flex-col lg:flex-row justify-between">
        <div>
          <h1 class="text-2xl py-8 underline">Languages</h1>
          <h3 class="py-2 text-lg">HTML</h3>
          <h3 class="py-2 text-lg">CSS</h3>
          <h3 class="py-2 text-lg">JavaScript</h3>
          <h3 class="py-2 text-lg">PHP</h3>
          <h3 class="py-2 text-lg">Java</h3>
          <h3 class="py-2 text-lg">SQL</h3>
        </div>
        <div>
          <h1 class="text-2xl py-8 underline">Frameworks</h1>
          <h3 class="py-2 text-lg">Bootstrap</h3>
          <h3 class="py-2 text-lg">Tailwind</h3>
          <h3 class="py-2 text-lg">VueJS</h3>
          <h3 class="py-2 text-lg">CodeIgniter</h3>
          <h3 class="py-2 text-lg">MaterializeCSS</h3>
        </div>
        <div>
          <h1 class="text-2xl py-8 underline">Softwares</h1>
          <h3 class="py-2 text-lg">Adobe Photoshop</h3>
          <h3 class="py-2 text-lg">Adobe XD</h3>
          <h3 class="py-2 text-lg">InVision</h3>
          <h3 class="py-2 text-lg">Figma</h3>
          <h3 class="py-2 text-lg">Office Suite</h3>
        </div>
      </div>
    </div> 

    <hr class="mt-16 lg:mt-32">

    <!-- Section5 -->
    <div class="container-about text-center text-white mt-16 lg:mt-24 pl-4 pr-4 md:p-0 mx-auto text-base md:text-2xl ">
      <h1 class="text-5xl text-center pb-8">Contact Me</h1>
      <p class="pb-16">Feel free to contact me at <span class="firstName">cmullin21@gmail.com</span> if you are interested in getting a website designed or developed! I will gladly be in touch as soon as possible!</p>
    </div> 

    <br>

  </div>
</template>

<script>
import navbar from '../components/navbar'
export default {
  components:{
    navbar
  }
}
</script>

<style>

</style>
