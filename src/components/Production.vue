<template>
  <div id="Production" class="tabcontent">
    <span onclick="this.parentElement.style.display='none'" class="topright">&times;</span>
    <h3>Production information</h3>
    <p>Hello hello, here is some shit about production.</p>
  </div>
</template>

<script>
export default {
  name: 'Production',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
