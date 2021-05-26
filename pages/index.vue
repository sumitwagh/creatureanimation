<template>
  <div class="bg-[#181818]">
    <header>
    <div>
      <video autoplay muted loop>
          <source src="~/assets/videos/background.mp4" type="video/mp4">
      </video>
     </div>
      <div>
        <div class="px-20 pt-2 relative">
          <nav class="flex items-center justify-between">
            <div>
              <NuxtLink to="/"
                ><img src="~/assets/img/logo.png"
              /></NuxtLink>
            </div>
            <div class="text-white font-bold">
              <NuxtLink class="text-[#FFC800]" to="/">Home</NuxtLink>
              <NuxtLink class="ml-8" to="/">Workshops</NuxtLink>
              <NuxtLink class="ml-8" to="/">Rings</NuxtLink>
              <NuxtLink class="ml-8" to="/">Tutors</NuxtLink>
              <NuxtLink class="ml-8" to="/">Testimonials</NuxtLink>
            </div>
            <div>
              <button
                class="bg-[#FFC800] rounded-md px-6 py-2 font-bold text-[#181818]"
              >
                Enroll Now
              </button>
            </div>
          </nav>
        </div>
        <div class="container mx-auto relative">
          <div class="mt-[600px]">
            <h1 class="text-4xl font-bold text-white text-center">
              Unleash the power to create a reality that lies within you
            </h1>
            <p
              class="text-md text-[#A5A5A5] text-center mt-8 px-24 font-semibold"
            >
              Our training specialised modules and custom-built courses are
              designed to be job oriented helping you learn the fine intricacies
              and nuances of various animation frameworks. We have had a chance
              of working in many big feature films and some recent ones such as
              Marvel Studios’ Avengers Endgame, Disney’s Aladdin and Jungle
              Book, WB’s Ready Player One and many more.
            </p>
            <div class="mt-6 flex justify-center">
              <button class="bg-[#FFC800] rounded-md px-6 py-2 font-bold mr-4 text-[#181818]">More For Students </button>
            <button class="rounded-md px-6 py-2 font-bold text-white">Hava a project for us?</button>
            </div>
          </div>
        </div>
      </div>
    </header>

    <div class="container mx-auto relative mt-48">
        <h2 class="text-lg font-bold text-center text-white">Workshops</h2>
      <div class="grid grid-cols-2 mt-24">
        <div>
           <div class="relative">
             <img src="~/assets/img/WS00.png"
              />
              <span class="bg-white text-[#181818] text-lg font-bold px-3 py-2 rounded-md absolute bottom-0 left-0 ml-4 mb-4">WS00</span>
           </div>
           <h3 class="text-2xl font-bold text-white pt-6">Creature Fundamentals</h3>
           <p class="text-lg text-[#747474] pt-2">One of the core beliefs of CAW is perfection and perfection lies in the details. This workshop targets creature locomotion to get a realistic reel that has personality, behaviour and organic feel to it. With one online class a week you can polish your locomotion skills right from the basics until you achieve the optimal level of perfection needed.</p>
        </div>
        <div>
         <div class="relative">
             <img src="~/assets/img/WS01.png"
              />
              <span class="bg-white text-[#181818] text-lg font-bold px-3 py-2 rounded-md absolute bottom-0 left-0 ml-4 mb-4">WS01</span>
           </div>
              <h3 class="text-2xl font-bold text-white pt-6">Simple body mechanics & behaviours</h3>
           <p class="text-lg text-[#747474] pt-2">The main focus is to deal with the animal with simple body mechanics with simple behavior in specific shots & goal is to get more believable and realistic locomotion. 
            Animating creature walks/ Runs to stops/sitting/ Lying down and more.</p>
        </div>
      </div>

      <div class="grid grid-cols-2 mt-16">
        <div>
           <div class="relative">
             <img src="~/assets/img/WS02.png"
              />
              <span class="bg-white text-[#181818] text-lg font-bold px-3 py-2 rounded-md absolute bottom-0 left-0 ml-4 mb-4">WS02</span>
           </div>
           <h3 class="text-2xl font-bold text-white pt-6">Complex body mechanics & Behaviours</h3>
           <p class="text-lg text-[#747474] pt-2">The main focus is to deal with the animal with complex body mechanics with Complex behaviour in specific shots and goal is to get more believable and realistic locomotion. </p>
        </div>
        <div>
         <div class="relative">
             <img src="~/assets/img/WS03.png"
              />
              <span class="bg-white text-[#181818] text-lg font-bold px-3 py-2 rounded-md absolute bottom-0 left-0 ml-4 mb-4">WS03</span>
           </div>
              <h3 class="text-2xl font-bold text-white pt-6">Creature interaction Sequence</h3>
           <p class="text-lg text-[#747474] pt-2">How to make a talking lion look real? By bringing out its personality through real-life acting and interactions. This workshop targets complex body mechanics by concentrating on the creature’s realistic movements and believable performance.</p>
        </div>
      </div>
         <div class="flex justify-center py-8">
           <button class="bg-[#FFC800] rounded-md px-6 py-2 font-bold mr-4 text-[#181818]">See More</button>
        </div>     
    </div>



    <div class="container mx-auto mt-24">
        <h2 class="text-lg font-bold text-center text-white">Our student's reels</h2>

      <div class="grid grid-cols-2 mt-12">

          <div class="relative">
             <img src="~/assets/img/showreel-1.png"
              />
            <div class="absolute bottom-0 left-0 flex items-center p-4">
                 <img class="border border-white rounded-full shadow-md" src="~/assets/img/aloke-sarkar.png"
              />
              <div class="ml-4">
                <span class="text-white text-lg font-bold">Aloke Sarkar</span>
                <p class="text-sm text-[#dddadb]">Animator</p>
              </div>
            </div>
          </div>

        <div class="relative">
            <img src="~/assets/img/showreel-2.png"
              />
            <div class="absolute bottom-0 left-0 flex items-center p-4">
                 <img class="border border-white rounded-full shadow-md" src="~/assets/img/swapnil-patil.png"
              />
              <div class="ml-4">
                <span class="text-white text-lg font-bold">Swapnil Paatil</span>
                <p class="text-sm text-[#dddadb]">Animator The Mill</p>
                </div>
              </div>
          </div>
      </div>

      <div class="grid grid-cols-2 mt-12">

          <div class="relative">
             <img src="~/assets/img/showreel-3.png"
              />
            <div class="absolute bottom-0 left-0 flex items-center p-4">
                 <img class="border border-white rounded-full shadow-md" src="~/assets/img/anivtha-aruna.png"
              />
              <div class="ml-4">
                <span class="text-white text-lg font-bold">Anivtha Aruna</span>
                <p class="text-sm text-[#dddadb]">Freelancer Animator</p>
              </div>
            </div>
          </div>

        <div class="relative">
            <img src="~/assets/img/showreel-4.png"
              />
            <div class="absolute bottom-0 left-0 flex items-center p-4">
                 <img class="border border-white rounded-full shadow-md" src="~/assets/img/ankit-singh.png"
              />
              <div class="ml-4">
                <span class="text-white text-lg font-bold">Ankit Singh</span>
                <p class="text-sm text-[#dddadb]">Animator</p>
                </div>
              </div>
          </div>
      </div>
      <div class="flex justify-center py-8">
          <button class="bg-[#FFC800] rounded-md px-6 py-2 font-bold mr-4 text-[#181818]">See More</button>
      </div>     
    </div>



    <div class="container mx-auto mt-24">
      <h2 class="text-lg font-bold text-center text-white">Testimonials</h2>
      <p class="text-lg text-[#A5A5A5] px-20 mt-12 text-center">
        Joining the workshop is one of the best thing i have done in my career. Thank you very much for all the advice and all the knowledge you have passed on to me on the workflow, tips and tricks which i use in my daily work. At first,I was so scared to work on four legged creature animation. I have no knowledge about it and not confident at all, but after the course am very confident from planning the shot to polishing the shot with a great quality. After this workshop and with my showreel i have got my first VFX job in Framestore and happy to share that have got change to work with movies like Fantastic beasts, guardians of galaxy 02 and paddington. 
      </p>
 
     <div class="w-full flex justify-center">
       <div class="py-8 flex justify-center">
         <div class="flex flex-col items-center">
          <img class="border border-white rounded-full shadow-md" src="~/assets/img/profile-1.png"/>
            <span class="text-white text-sm font-bold mt-2">Anivtha Aruna</span>
         </div>
        <div class="ml-8"><img src="~/assets/img/profile-2.png"/> </div>
        <div class="ml-8"><img src="~/assets/img/profile-3.png"/></div>
        <div class="ml-8"><img src="~/assets/img/profile-4.png"/></div>
        <div class="ml-8"><img src="~/assets/img/profile-5.png"/></div>
        <div class="ml-8"><img src="~/assets/img/profile-6.png"/></div>
      </div>
     </div>
      </div>

    <div class="container mx-auto mt-24">
      <h2 class="text-lg font-bold text-center text-white">Our Creature Rings</h2>

      <div class="grid grid-cols-3 gap-4 mt-12">
        <div>
          <img src="~/assets/img/crature-ring-01.png" />
        </div>
        <div>
          <img src="~/assets/img/crature-ring-02.png" />
        </div>
        <div>
          <img src="~/assets/img/crature-ring-03.png" />
        </div>
        <div>
          <img src="~/assets/img/crature-ring-04.png" />
        </div>
        <div>
          <img src="~/assets/img/crature-ring-05.png" />
        </div>
        <div>
          <img src="~/assets/img/crature-ring-06.png" />
        </div>
      </div>
        <div class="flex justify-center py-8">
          <button class="bg-[#FFC800] rounded-md px-6 py-2 font-bold mr-4 text-[#181818]">See More</button>
      </div>     
    </div>


    <div class="container mx-auto mt-24">
      <h2 class="text-lg font-bold text-center text-white">Recent Movies Mentors Worked </h2>

      <div class=" mt-12">
          <img src="~/assets/img/logos.png" />
      </div>
    </div>

    <div class="container mx-auto">


    </div>

    </div>
  </div>
</div>    
</div>
</template>

<script>
export default {};
</script>

<style scoped>
.background {
  background-image: url("~assets/img/hero-banner.png");
  height: 1000px;
}

video {
    position: absolute;
    left: 50%;
    top: 50%;
    /* The following will size the video to fit the full container. Not necessary, just nice.*/
    min-width: 100%;
    min-height: 100%;
    -webkit-transform: translate(-50%,-50%);
    -moz-transform: translate(-50%,-50%);
    -ms-transform: translate(-50%,-50%);
    transform: translate(-50%,-50%);
    z-index: 0;
}
</style>
