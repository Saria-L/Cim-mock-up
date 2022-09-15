<template>
  <div id="Blabla" class="tabcontent">
    <span onclick="this.parentElement.style.display='none'" class="topright">&times;</span>
    <h3>Blabla</h3>
    <p>Anything you want to blabla see about your amazing machine</p>
  </div>
</template>

<script>
export default {
  name: 'Blabla',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
