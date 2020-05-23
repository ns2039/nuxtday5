<template>
  <div>
    <nuxt />
    <PageHeader />
    <Migration />
    <PageFooter />
  
  </div>
</template>

<script>
import PageHeader from '~/components/common/PageHeader.vue'
import Migration from '~/components/top/Migration.vue'
import PageFooter from '~/components/common/PageFooter.vue'

export default{
  components: {
    PageHeader,
    Migration,
    PageFooter

  }
}

</script>