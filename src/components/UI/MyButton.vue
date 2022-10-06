<template>
  <button class="btn">
    <slot></slot>
  </button>
</template>

<script>
export default {
  name: 'my-button'
}
</script>

<style>
  .btn {
    /* margin: 15px; */
    border: 1px solid #000;
    padding: 5px;
  }
</style>