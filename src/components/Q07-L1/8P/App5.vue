<template>
  <div>
    <h2>관심있는 k-pop 가수?</h2>
    <hr />
    <ul>
      <checkboxItem v-for="doli in idols" :key="doli.id" :id="doli.id" :name="doli.name" :checked="doli.checked" />
    </ul>
  </div>
</template>

<script>
import CheckboxItem from './CheckboxItem5.vue';

export default {
  name: 'App',
  components: { CheckboxItem },
  data() {
    return {
      idols: [
        { id: 1, name: 'BTS', checked: true },
        { id: 2, name: 'asppa', checked: false },
        { id: 3, name: 'EXO', checked: false },
        { id: 4, name: 'Newjeanse', checked: false },
      ],
    };
  },
};
</script>
