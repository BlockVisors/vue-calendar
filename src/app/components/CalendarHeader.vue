<template>
  <div id="calendar-head" class="container">
    <div class="columns is-mobile">
      <div id="header">
        <h1>Dameon's Calendar App</h1>
    </div>
    </div>
  </div>
</template>

<script>
import { store } from '../store.js';

export default {
  name: 'CalendarHeader',
  data () {
    return {
      sharedState: store.state
    }
  },
  components: {
    
  }
}
</script>

<style lang="scss" scoped>
#calendar-head {
  margin-bottom: 50px;
  .column {
    padding: 0 0 0 0;
  }
}
#header {
   font-size: 40px;
   text-align: center;
   color: antiquewhite; 
}
</style>