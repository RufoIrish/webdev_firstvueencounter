<template>
  <div>
    <Header/>
   
  </div>
</template>
<script>
import Header from "@/components/Header";

export default {
  name: "app",
  components:{
    Header
  }
};
</script>

<style>
* {
  box-sizing: border-box;
  margin: 0;
  background-color: beige;
}
nav {
  margin-left: 44%;
}
</style>
