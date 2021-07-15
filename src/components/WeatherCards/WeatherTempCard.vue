<template>
  <li class="widjet-temp-item">
    {{ converterKelvin(temp) }}°
  </li>
</template>

<script>
import { converterKelvin } from '@/utils/converter';

export default {
  // eslint-disable-next-line
  props: ['temp'],
  methods: {
    converterKelvin,
  },
};
</script>

<style>
</style>
