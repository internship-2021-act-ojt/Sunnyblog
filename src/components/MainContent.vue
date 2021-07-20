<template>
<div class="mainContent">
  <MainTop/>
  <MainBottom/>
</div>
</template>

<script>
import MainTop from "./MainTop";
import MainBottom from "./MainBottom";
export default {
  name: "MainContent",
  components: {MainBottom, MainTop}
}
</script>

<style scoped>
.mainContent{
  width: 100%;
  height: 100%;

  padding: 48px 35px;
  display: flex;
  flex-direction: column;


}
</style>