<template>
  <div>
    <svg-icon icon-class="github" @click="goto" />
  </div>
</template>

<script>
export default {
  name: 'BaizeGit',
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
