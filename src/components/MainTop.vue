<template>
  <div class="mainTop">
    <div class="topButtonContainer">

    </div>
    <div class="topTitleContainer">
      <div></div>
    </div>
  </div>
</template>

<script>
export default {
  name: "MainTop"
}
</script>

<style scoped>
.mainTop {

  height: 500px;


}

.topButtonContainer {
  height: 10%;
  background-color: darkorange;
  display : flex;
  justify-content: flex-end;
}

.topTitleContainer {
  height : 90%;
  background-color: lightsteelblue;
  display : flex;
  justify-content: center;
}

</style>