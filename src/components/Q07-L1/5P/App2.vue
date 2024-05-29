<template>
  <div>
    <h2>APP 컴포넌트</h2>
    <hr />
    <ul>
      <CheckboxItem2 />
      <CheckboxItem2 />
      <CheckboxItem2 />
      <CheckboxItem2 />
    </ul>
  </div>
</template>

<script>
import CheckboxItem2 from './CheckboxItem2.vue';

export default {
  name: 'App',
  components: { CheckboxItem2 },
};
</script>
