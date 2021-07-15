<template>
  <li class="widjet-precipitation-item">
    {{ rain ? rain["1h"] : 0 }} мм
  </li>
</template>

<script>
export default {
  // eslint-disable-next-line
  props: ['rain'],
};
</script>

<style>
</style>
