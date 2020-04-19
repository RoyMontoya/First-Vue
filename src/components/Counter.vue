<template>
  <div class="hello">
    <h1>{{ count }}</h1>
    <Button @clicked="count++" />
  </div>
</template>

<script>

import Button from './Button'

export default {
  name: 'Counter',
  components: {
    Button
  },
  data: function() {
    return {
      count: 0
      }
  },
}
</script>

<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
