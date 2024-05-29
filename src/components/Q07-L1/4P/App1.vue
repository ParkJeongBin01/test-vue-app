<template>
  <div>
    <h2>APP 컴포넌트</h2>
    <hr />
    <ul>
      <CheckboxItem1 />
      <CheckboxItem1 />
      <CheckboxItem1 />
      <CheckboxItem1 />
    </ul>
  </div>
</template>

<script>
import CheckboxItem1 from './CheckboxItem1.vue';

export default {
  name: 'App',
  components: { CheckboxItem1 },
};
</script>
