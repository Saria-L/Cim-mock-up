<template>
  <div id="Status" class="tabcontent">
    <span onclick="this.parentElement.style.display='none'" class="topright">&times;</span>
    <h3>Current Status</h3>
    <p>Current status is A-OK.</p>
  </div>
</template>

<script>
export default {
  name: 'Status',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
