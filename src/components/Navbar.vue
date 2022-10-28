<template>
 
   <nav>
     <!--desktop Menu-->
<div class=" flex flex-wrap items-center text-base justify-center h-24 bg-gray-900 text-white sticky top-0 z-50 ">
   
         <div class=" float: left ">
   

           <!--image-->

          <img  class="w-45 h-20" src="../assets/Moonbeam-Logo-Final-500px.png " alt=""/>
     
     
         </div>
            

                 
         <!--menu-->

                         <div class="hidden md:flex items-center ">
                    
                         <div class="hidden  md:flex items-center px-2 cursor-pointer" id="bars"></div>
    

      

      <a href="Home.vue" class="p-2 mr-3"><router-link to="/add">Builders</router-link></a>
       <a href="#" class="p-2 mr-3 ">Community</a>
      <a href="#" class="p-2 mr-3">Networks</a>
      <a href="#" class="p-2 mr-3">Tokens</a>
      <a href="#" class="p-2 mr-3">About</a>

      <button class="border border-white text-white  duration-500 px-6 py-2 mx-4 hover:border-pink-700 hover:text-pink-700 rounded">
        Foundation
      </button>

      <button class="bg-pink-600 text-white  duration-500 px-6 py-2 mx-4 hover:bg-pink-800 rounded">
        Launch App
      </button>


      <!--icons-->
     <div class="px-2">
 <a href="#" class="mx-3 text-gray-600 transition-colors duration-200 transform dark:text-gray-200 hover:text-gray-500 dark:hover:text-blue-400 hover:animate-bounce  " aria-label="Github  ">
      <i class="bi bi-twitter"></i>
 </a>

 <a href="#" class="mx-3 text-gray-600 transition-colors duration-200 transform dark:text-gray-200 hover:text-gray-500 dark:hover:text-blue-400 hover:animate-bounce  " aria-label="Github  ">
      <i class="bi bi-youtube"></i>
 </a>

 <a href="#" class="mx-3 text-gray-600 transition-colors duration-200 transform dark:text-gray-200 hover:text-gray-500 dark:hover:text-blue-400 hover:animate-bounce  " aria-label="Github  ">
      <i class="bi bi-github"></i>
 </a>

 <a href="#" class="mx-3 text-gray-600 transition-colors duration-200 transform dark:text-gray-200 hover:text-gray-500 dark:hover:text-blue-400 hover:animate-bounce  " aria-label="Github  ">
      <i class="bi bi-telegram"></i>
 </a>

 <a href="#" class="mx-3 text-gray-600 transition-colors duration-200 transform dark:text-gray-200 hover:text-gray-500 dark:hover:text-blue-400 hover:animate-bounce  " aria-label="Github  ">
      <i class="bi bi-map-fill"></i>
 </a>

 <a href="#" class="mx-3 text-gray-600 transition-colors duration-200 transform dark:text-gray-200 hover:text-gray-500 dark:hover:text-blue-400 hover:animate-bounce  " aria-label="Github  ">
      <i class="bi bi-discord"></i>
 </a>

     </div>            
               



                    <!--button show model menu-->

                    <div class="md:hidden flex items-center ">
                         
               <button @click="showMobileMenu = !showMobileMenu" class="py-5 px-2">
                         
                              <i class="bi bi-list " ></i>
               </button>
                         
                    </div>

                    </div>
                         
                    
                   
               
          
   </div>

     <!--mobile menu-->
     <div class="  md:hidden w-full bg-teal-400 text-green-100  " :class="{hidden:showMobileMenu}">
          <a href="#" class="block  px-4  hover:text-white">Builders</a>
          <a href="#" class="block  px-4  hover:text-white">Community</a>
          <a href="#" class="block  px-4  hover:text-white">Networks</a>
          <a href="#" class="block  px-4  hover:text-white">Tokens</a>
         <a href="#" class="block  px-4  hover:text-white">About</a>
         <a href="#" class="block  px-4  hover:text-white">Foundation</a>
         <a href="#" class="block  px-4  hover:text-white">Launch App</a>


     


      


      <!--icons-->

 <a href="#" class="mx-3 text-gray-600 transition-colors duration-200 transform dark:text-gray-200 hover:text-gray-500 dark:hover:text-blue-400 hover:animate-bounce  " aria-label="Github  ">
      <i class="bi bi-twitter"></i>
 </a>

 <a href="#" class="mx-3 text-gray-600 transition-colors duration-200 transform dark:text-gray-200 hover:text-gray-500 dark:hover:text-blue-400 hover:animate-bounce  " aria-label="Github  ">
      <i class="bi bi-youtube"></i>
 </a>

 <a href="#" class="mx-3 text-gray-600 transition-colors duration-200 transform dark:text-gray-200 hover:text-gray-500 dark:hover:text-blue-400 hover:animate-bounce  " aria-label="Github  ">
      <i class="bi bi-github"></i>
 </a>

 <a href="#" class="mx-3 text-gray-600 transition-colors duration-200 transform dark:text-gray-200 hover:text-gray-500 dark:hover:text-blue-400 hover:animate-bounce  " aria-label="Github  ">
      <i class="bi bi-telegram"></i>
 </a>

 <a href="#" class="mx-3 text-gray-600 transition-colors duration-200 transform dark:text-gray-200 hover:text-gray-500 dark:hover:text-blue-400 hover:animate-bounce  " aria-label="Github  ">
      <i class="bi bi-map-fill"></i>
 </a>

 <a href="#" class="mx-3 text-gray-600 transition-colors duration-200 transform dark:text-gray-200 hover:text-gray-500 dark:hover:text-blue-400 hover:animate-bounce  " aria-label="Github  ">
      <i class="bi bi-discord"></i>
 </a>
     </div>
   </nav>
     
         
</template>

<script setup>
import{ref} from"vue";

const showMobileMenu = ref(true);

</script>
