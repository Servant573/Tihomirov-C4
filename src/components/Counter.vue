<template>
  <div>
    <h2>Счетчик задач</h2>
    <p>{{countTask}}</p>
  </div>
</template>

<script>
export default {
  props: ['countTask'],
};
</script>
