<template>
  <div>
    <div>
      <center>
        <h1>EcoGreen</h1>
        <b-navbar>
          <h3>
            <router-link to="/">Home</router-link>&nbsp;
            <router-link to="./about">About</router-link>
          </h3>
        </b-navbar>
        <hr />
      </center>
    </div>
  </div>
</template>
<script>

export default {
  name: "Header",

};
</script>
<style scoped>
* {
  box-sizing: border-box;
  margin: 0;
}
h3 {
  margin-left: 45%;
}
</style>