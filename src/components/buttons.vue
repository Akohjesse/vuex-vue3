<template>
      <div class="buttons">
       <button @click="$store.dispatch('decreaseCounter')">-</button>
      <button @click="$store.dispatch('increaseCounter')">+</button>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.buttons{
   button{
    display:inline;
    margin:0 10px;
    font-size: 1.4em;
    width:90px;
   }
}
</style>