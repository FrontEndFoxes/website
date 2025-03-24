<script setup>
defineProps({
  msg: {
    type: String,
    required: true,
  },
})
</script>

<template>
  <div class="greetings">
    <h1 class="green">{{ msg }}</h1>
    <h3>
      Vue Vixens was a 501(c)(3) non-profit organization that taught workshops
      and provided scholarships to foxy people who identify as women. We want to thank the community and our sponsors for for your support. 
      We rebranded as Front-End Foxes, Inc., and continued the mission during COVID-19 by creating a global, 
      free-of-charge, boot camp teaching cohorts of students web development skills, led by the community. Visit the 
      <a href="https://ff-school.jenlooper.com/" _target="blank">Front-End Foxes School Web Site</a> to learn more. You can view our Boot Camp curriculum <a href="https://ff-school.jenlooper.com/curriculum" target="_blank">here</a> and our Workshop (skulk) curriculum <a href="frontendfoxes.github.io/curriculum/" target="_blank">here</a>. Ever been curious what kind of a fox you might be? Take our iconic personality quiz <a href="https://vv-quiz.netlify.app/" target="_blank">here</a>, for fun.
    </h3>
  </div>
</template>


