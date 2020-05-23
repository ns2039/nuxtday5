<template>
  <div id="main-content">
      <Hero />
      <Mission />
      <Results />
      <Features />
      <Business />
      <Member />
      <Update />
      <Recruit />
      <Compamy />

 

  </div>
</template>

<script>
import Hero from '~/components/top/Hero.vue'
import Mission from '~/components/top/Mission.vue'
import Results from '~/components/top/Results.vue'
import Features from '~/components/top/Features.vue'
import Business from '~/components/top/Business.vue'
import Member from '~/components/top/Member.vue'
import Update from '~/components/top/Update.vue'
import Recruit from '~/components/top/Recruit.vue'
import Company from '~/components/top/Company.vue'



export default {
  components: {
    Hero, 
    Mission,
    Results,
    Features,
    Business,
    Member,
    Update,
    Recruit,
    Company,
 
  }}
</script>