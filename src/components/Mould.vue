<template>
  <div id="Mould" class="tabcontent">
    <span onclick="this.parentElement.style.display='none'" class="topright">&times;</span>
    <h3>Moulding information</h3>
    <p>I dont know, maybe like, pattern number?</p>
  </div>
</template>

<script>
export default {
  name: 'Mould',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
