<template>
  <footer>
      <p>{{ footerText }}</p>
  </footer>
</template>

<script>
  export default {
    data() {
      return{
        footerText: '© DZANABLAZEVIC.DK, ALL RIGHTS RESERVED'
      }
    }
  }
</script>

<style lang="scss" scoped>
footer {
  color: #C3B1A6;
  text-align: center;
  height: 10px;
}
</style>