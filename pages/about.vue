<template>
  <div class="h-screen bg-gradient-to-br from-grey to-black text-white">
    <Navbar/>
    <section class="p-5 pt-10 lg:w-6/12 lg:p-24 lg:grid lg:justify-center" >
      <h1 class="text-6xl font-barlow  lg:text-9xl lg:w-full">
        About 
        <span class="text-light-blue">
          Me
        </span>
      </h1>
      <section class="pt-10 w-52 lg:w-6/12 leading-relaxed lg:text-3xl">
        <p>
          So, I am a student studying in 10th grade at the moment, living in the bustling city of Kolkata. 
        </p>
        <p class="pt-7">
          I am fully self taught, teaching myself programming for 
          <span class="text-light-blue">
            4 
          </span>
            years and 3d modelling blender for 
          <span class="text-light-blue">
            2.
          </span>
        </p>
      </section>
    </section>
  </div>
</template>



<script>
  export default {
    name: 'About'
  }
</script>
