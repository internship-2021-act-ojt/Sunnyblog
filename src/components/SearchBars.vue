<template>
  <div class="searchBars">
    <div class="searchBox">
      <div>Search</div>
      <input/>

    </div>
  </div>

</template>

<script>
export default {
  name: "SearchBars"
}
</script>

<style scoped>
.searchBars {
  height: 60%;

  border-top: solid lightgrey 1px ;

}
.searchBox {
  height : 70px;
  width : 230px;
  margin-top: 35px;
  padding : 25px 0 0;
  background-color: lightsteelblue;

}
</style>