<template>
  <div class="TheSite">
    <TopHeader />
    <main class="Site-content">
      <nuxt />
    </main>
    <TheFooter />
  </div>
</template>

<script>
import TopHeader from '@/components/TopHeader'
import TheFooter from '@/components/TheFooter'
export default {
  components: {
    TopHeader,
    TheFooter
  }
}
</script>

<style>
.Site {
  display: flex;
  min-height: 100vh;
  flex-direction: column;
}

.Site-content {
  flex: 1;
}
</style>
