<template>
  <div class="menuBars">
    <div class="menuItems" v-for="item in webItems" v-bind:key="item.title">
      {{item.title}}
    </div>
  </div>
</template>

<script>
export default {
  name: "MenuBars",
  props : {
    webItems : []
  }
}
</script>

<style scoped>
.menuBars {
  height: 30%;
  background-color: white;
  width : 100%;
  display : flex;
  flex-direction: column;
  justify-content: space-between;

}
.menuItems {
  width : 100%;
  margin-bottom: 20px;
  padding-left : 5px;
}
</style>