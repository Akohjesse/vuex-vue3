<template>
     <div class="counter-square">
      {{$store.state.counter}} <sup>2</sup> = {{$store.getters.counterSquare}}
    </div>
</template>

<script>
export default {
name: 'Countersquare'
}
</script>

<style>

</style>