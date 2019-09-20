<template>
  <div id="app">
    <CalendarHeader />
    <CalendarWeek />
    <CalendarEntry />
  </div>
</template>

<script>
import CalendarWeek from './components/CalendarWeek.vue';
import CalendarEntry from './components/CalendarEntry.vue';
import CalendarHeader from './components/CalendarHeader.vue';

export default {
  name: 'App',
  components: {
    CalendarWeek,
    CalendarEntry,
    CalendarHeader
  }
}
</script>

<style lang="scss">
html, body {
  height: 100%;
}
</style>

<style lang="scss" scoped>
#app {
  height: inherit;
  background: #104480;
  display: flex;
  flex-direction: column;
  align-items: center;
  -webkit-align-items: center;
  justify-content: center;
  -webkit-justify-content: center;
}
</style>

