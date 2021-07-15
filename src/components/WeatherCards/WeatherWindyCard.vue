<template>
  <li class="widjet-windy-item">
    {{ wind_speed.toFixed() }} м/с
  </li>
</template>

<script>
export default {
  // eslint-disable-next-line
  props: ['wind_speed'],
};
</script>

<style>

</style>
