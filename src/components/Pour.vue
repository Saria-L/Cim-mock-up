<template>
  <div id="Pour" class="tabcontent">
    <span onclick="this.parentElement.style.display='none'" class="topright">&times;</span>
    <h3>Pouring Information</h3>
    <p>Maybe just a nice picture of the PU</p>
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
