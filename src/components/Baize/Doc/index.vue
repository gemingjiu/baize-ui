<template>
  <div>
    <svg-icon icon-class="question" @click="goto" />
  </div>
</template>

<script>
export default {
  name: 'BaizeDoc',
  data() {
    return {
      url: 'https://github.com/gemingjiu/baize'
    }
  },
  methods: {
    goto() {
      window.open(this.url)
    }
  }
}
</script>
