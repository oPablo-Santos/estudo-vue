<template>
  <div id="main">
    <h1>Make Your Burger</h1>
  </div>
</template>
<script>
export default {
    name: "Banner"
};
</script>
<style scoped>
#main {
  background-image: url("/public/img/burger.jpg");
  background-position: 0 -80%;
  background-size: cover;
  height: 250px;
  display: flex;
  align-items: center;
  justify-content: flex-start;
}

#main h1{
    color: #fff;
    text-align: center;
    font-size: 60px;
    background-color: #222;
}
</style>
