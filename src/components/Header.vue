<template>
  <header>
    {{ title }}
    <Button text='Add' color='green' />
    <!-- <Button text='Update' color='blue' /> -->
    <!-- <Button text='Delete' color='red' /> -->
  </header>
</template>

<script>
import Button from "./Button.vue";
export default {
  name: "Header",
  props: {
    title: String,
  },
  components: {
    Button,
  },
};
</script>
<style scoped>
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 20px;
}
</style>