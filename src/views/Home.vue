<template>
  <div class="home">
    <Top/>
    <RunList/>
    
  </div>
</template>

<script>
// @ is an alias to /src
import Top from '@/components/Top.vue'
import RunList from '@/components/RunList.vue'

export default {
  name: 'home',
  components: {
    Top,RunList
  }
}
</script>
