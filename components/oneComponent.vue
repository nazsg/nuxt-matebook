<template>
  <div>
      <h2 @click="$emit('close')">component one</h2>
      <p @click="$emit('close2')">
        Lorem ipsum dolor, sit amet consectetur adipisicing elit. Dignissimos placeat dolores reprehenderit perferendis eaque. Expedita at hic sapiente odio odit magni nemo, corporis, minima cum nesciunt consequatur ipsum dignissimos explicabo.
      <p @click="$emit('close3')">another click test</p>
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>