<template>
  <div class="text">
      <input v-model="colorCode" type="text" placeholder="Enter color code">
    </div>
</template>

<script>
export default {
computed:{
    colorCode: {
       get(){
      return this.$store.state.colorCode
    },
    set(newVal){
        this.$store.dispatch('setColorCode', newVal)
    }
    }
  }
}
</script>

<style>

</style>