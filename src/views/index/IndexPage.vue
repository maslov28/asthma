<template>
  <div>
    <header-section></header-section>
    <start-section></start-section>
  </div>
</template>

<script>
import HeaderSection from '@/components/blocks/header/header-section.vue'
import StartSection from '@/components/blocks/start-section/start-section.vue'

export default {
  components: {
    HeaderSection,
    StartSection
  }
}
</script>
