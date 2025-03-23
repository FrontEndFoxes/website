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
      <a href="https://ff-school.jenlooper.com/" _target="blank">Front-End Foxes School Web Site</a> to learn more.
    </h3>
  </div>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  position: relative;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
