<script setup>

  /* defineProps : 부모로부터 전달 받을 값을 정의하는 함수 */

  const props = defineProps({
    message : String
    /* 부모로부터 전달 받은 message가 String 타입인지 검사 */
  });
</script>

<template>
  <h3>전달 받은 props : {{ 부모로부터 받은 값 }}</h3>
</template>

<style scoped>

</style>