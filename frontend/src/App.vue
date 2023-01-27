<template>
  <div id="app">
    <Calendar />
  </div>
</template>

<script>
import Calendar from './components/Calendar-App.vue';
export default {
  name: 'App',
  data: () => ({
    message: 'HelloWorld!',
  }),
  components: {
    Calendar,
  },
};
</script>
