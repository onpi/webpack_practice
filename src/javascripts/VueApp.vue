<template>
  <P>{{ message }}</P>
</template>

<script>
export default {
  data: () => {
    console.log('Vue.js is installed');
    return {
      message: 'Hey, this is Vue!',
    };
  }
};
</script>

<style scoped>
p{
  color: green;
}
</style>
