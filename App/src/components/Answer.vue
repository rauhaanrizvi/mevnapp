<template>
  <div class='answer'> 
    <slot></slot>
  </div>
</template>

<script>
export default {
  name: 'Answer',
  // props: ['answer']
}
</script>

<style>
.answer{
  font-size: 18;
}
</style>
