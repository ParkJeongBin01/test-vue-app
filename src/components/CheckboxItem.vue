<template>
  <li><input type="checkbox" :checked="doli2.checked" />{{ doli2.name }}</li>
</template>

<script>
export default {
  name: 'CheckboxItem',
  props: ['idols'],
};
</script>
