<template>
  <div>
    <button v-on:click="clicked">Click</button>
  </div>
</template>

<script>

export default {
  name: 'Button',
  methods:{
    clicked() {
        this.$emit('clicked');
    }
  }
}
</script>
