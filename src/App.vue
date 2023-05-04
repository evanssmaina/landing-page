<template>
  <div  class="overflow-hidden">
    <div class="bg-cover bg-center bg-[url('./Assets/background.png')]">
      <nav class="flex justify-between pt-3 lg:px-24 px-5 pb-20 items-center">
    <section>
        <img src="./Assets/Logo.svg" alt="">
    </section>

    <section class="flex space-x-1 invisible lg:visible md:visible">
        <img src="./Assets/Search.svg" alt="">
        <h2 class="p-5">Sign in</h2>
        <button class='bg-black text-white rounded-md lg:p-5 md:px-7 '>
            <span class="font-semibold">Get started</span> - <span class="font-light">it's free</span>
        </button>

       
           <img src="./Assets/Hamburger.svg" alt="" class='visible lg:invisible md:invisible'>

        <div class='w-full hidden' id='navbar-hambarger'>
        <img src="./Assets/Search.svg" alt="">
        <h2 class="p-5">Sign in</h2>
        <button class='bg-black text-white rounded-md lg:p-5 md:px-7 '>
            <span class="font-semibold">Get started</span> - <span class="font-light">it's free</span>
        </button>
        </div>
        
    </section>
   </nav>


   <article class='object-center lg:px-20 px-5'>
    <h1 class='text-5xl font-bold text-center pb-7 leading-relaxed'>
        Gorgeous Code Snippets
    </h1>

    <p class="text-center">
        With Snipper, create fully customizable code snippets in matter of seconds <br>right from your browser.
    </p>
 <div class="flex justify-center">
    <button class='bg-black text-white px-20 py-3 items-center rounded-md ml-2 my-3 lg:p-5 flex'>
        <h3 class="text-center flex ml-auto">
          <span class="font-semibold text-center">Get started</span>  -  <span class="font-light">it's free</span> 
        </h3>        
        </button>
 </div>
    

    <h3 class="text-center mb-16 mt-5 lg:mt-1 lg:justify-center">
        No credit card required.
    </h3>
   </article>

   <section class="flex justify-center">
    <img src="./Assets/Snippet.png" alt="" class="h-full justify-center w-10/12 px-">
   </section>
    </div>
       

   <div class=" lg:px-24 px-5 md:px-10 pt-10 items-center lg:space-x-20 lg:flex grid grid-row-2 lg:grid-cols-2">


    <section class="lg:order-last md:justify-center md:px-10">
        <img src="./Assets/Customizable.png" alt="" class="lg:w-11/12 md:w-3/4">
    </section>

    <section class="lg:order-first lg:col-span-4">
        <h2 class="text-2xl md:text-4xl font-bold pb-3 pt-9">A fully customizable code snippet editor</h2>
        <p class="pb-4">Fully customize the color scheme of your code snippet, or use our own premade color schemes. Export your code snippets in JPG, PDF, PNG, or any other 10+ common extensions.</p>
        <button class='bg-black text-white p-5 rounded justify-center'>
            <span class="font-semibold">Get started</span> - <span class="font-light">it's free</span>
        </button>
    </section>

   </div>


   <div class="lg:flex md:px-10 md:flex md:justify-between lg:justify-between lg:px-24 px-5 items-center lg:py-20 pb-5 pt-10 space-y-4">
    <section><img src="./Assets/Logo.svg" alt=""></section>
    <section>
       <ul class="flex lg:gap-x-4 gap-x-4">
        <li><a href="">Terms and Conditions</a></li>
        <li><a href="">Privacy Policy</a></li>
       </ul>
    </section>
   </div>


  </div>
</template>