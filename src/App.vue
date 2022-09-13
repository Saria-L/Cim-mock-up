<template>
  <div id="app">
    <div class="tab">
  <button class="tablinks" onclick="openCIM(event, 'Status')">Status</button>
  <button class="tablinks" onclick="openCIM(event, 'Production')">Production</button>
  <button class="tablinks" onclick="openCIM(event, 'Mould')">Mould</button>
  <button class="tablinks" onclick="openCIM(event, 'Pour')">Pour</button>
  <button class="tablinks" onclick="openCIM(event, 'Blabla')">Blabla</button>
  <input type="text" placeholder="Pattern, date, blabla">
</div>
 
 
    <Status msg="HVADSÅ"/>
    <Production msg="YOYOYOYO"/>
  </div>
</template>


<script>
import Status from './components/Status.vue'
import Production from './components/Production.vue'
import Mould from './components/Mould.vue'
import Pour from './components/Pour.vue'
import Blabla from './components/Blabla.vue'

export default {
  name: 'App',
  components: {
    Status, 
    Production
  }
}

// function openCIM(evt, cimData) {
//   var i, tabcontent, tablinks;
//   tabcontent = document.getElementsByClassName("tabcontent");
//   for (i = 0; i < tabcontent.length; i++) {
//     tabcontent[i].style.display = "none";
//   }
//   tablinks = document.getElementsByClassName("tablinks");
//   for (i = 0; i < tablinks.length; i++) {
//     tablinks[i].className = tablinks[i].className.replace(" active", "");
//   }
//   document.getElementById(cimData).style.display = "block";
//   evt.currentTarget.className += " active";
// }
 

</script>

<style>
body {font-family: Calibri;}
 
/* Style the tab */
.tab {
  overflow: hidden;
  border: 1px solid #ccc;
  background-color: #f1f1f1;
}
 
/* Style the buttons inside the tab */
.tab button {
  background-color: inherit;
  float: left;
  border: none;
  outline: none;
  cursor: pointer;
  padding: 14px 16px;
  transition: 0.3s;
  font-size: 17px;
}
 
/* Change background color of buttons on hover */
.tab button:hover {
  background-color: #ccc;
}
 
/* Create an active/current tablink class */
.tab button.active {
  background-color: #ccc;
}
 
/* Style the tab content */
.tabcontent {
  display: none;
  padding: 6px 12px;
  border: 1px solid #ccc;
  border-top: none;
}
 
/* Style the close button */
.topright {
  float: right;
  cursor: pointer;
  font-size: 28px;
}
.topright:hover {color: black;}
 
/* Style search function */
.tab input[type=text] {
  float: right;
  padding: 6px;
  margin-top: 8px;
  margin-right: 16px;
  border: none;
  font-size: 17px;
  font-color: ;
}
 
#app {

}
</style>
