<template>
  <div id="app">
  
  <navbar />
  <router-view/>
  <pageFooter />

  </div>
</template>

<script>
import navbar from '@/components/navbar'
import pageFooter from '@/components/pageFooter'
export default {
  components: {
    navbar, pageFooter
  }
}
</script>

<style>

</style>
