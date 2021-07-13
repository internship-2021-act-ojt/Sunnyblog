<template>
    <div class="navBar">
      <div class="title">webflow Blog</div>
      <MenuBars :webItems="webItems"/>
      <SearchBars/>
      <FootBar/>
    </div>
</template>

<script>
  import MenuBars from "./MenuBars";
  import SearchBars from "./SearchBars";
  import FootBar from "./FootBar";
  export default {
    name: "NavBar",
    components: {FootBar, SearchBars, MenuBars},
    data : function() {
      return {
        webItems : [
          {title : "New"},
          {title : "Popular"},
          {title : "Ebooks"},
          {title : "Reading lists"},
          {title : "Topics"},
          {title : "Featured"},
        ]
      }
    }

  }
</script>

<style scoped>
.navBar {
  padding: 48px 35px;
  width: 380px;
  height: 100%;
  background-color: antiquewhite;
  display : flex;
  flex-direction: column;
  border-right: black solid 1px;
}

.title {
  margin : 40px 0 70px 0;
  font-size: 20px;
}

</style>