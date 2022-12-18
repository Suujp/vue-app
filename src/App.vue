<template>
  <div id="app">
    <h1>{{ message }} : {{ uuid }}</h1>
  </div>
</template>

<script>
import { v4 as uuidv4 } from 'uuid'

export default {
  name: 'App',
  components: {

  },
  data: function() {
    return {
      message: 'uuid',
      uuid: uuidv4(),
    }
  }
}
</script>
