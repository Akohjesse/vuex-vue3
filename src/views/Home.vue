<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
   <Counter/>
   <Countersquare/>
   <buttons class="buttons"/>
   <Color-code/>
  </div>
</template>

<script>
export default {
  name: 'Home',
  components: {
    'Counter': require('@/components/counter.vue').default, 
    'Countersquare': require('@/components/counterSquared.vue').default,
    'buttons': require('@/components/buttons.vue').default,
    'Color-code': require('@/components/colorcode.vue').default
  }
}
</script>


<style lang="scss" scoped>
div{
   margin-bottom: 20px;
}
.counter{
 font-size: 80px;
}
</style>