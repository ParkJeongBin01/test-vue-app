<template>
  <li><input type="checkbox" :checked="doli1.checked" />{{ doli1.name }}</li>
</template>

<script>
export default {
  name: 'CheckboxItem',
  props: ['doli1'],
};
</script>
