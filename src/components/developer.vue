<template>
  <div>
      <h3>
          <img :src="image" />
          {{name}}
          {{description}}
          <br />
          {{description}}
      </h3>
      <br />
      <br />
  </div>
</template>
<script>
export default {
  name: "developer",
    props: {
        name: String,
        image: String,
        description: String
    }
};
</script>
<style scoped>
h1 {
  margin-top: 5%;
}
h3 {
  width: 300px;
  border: 2px solid black;
  padding: 50px;
  margin: 20px;
  /* text-align: center; */
  margin-left: 0%;
  background-color: white;
  /* float: left; */
}
image {
  height: 200px;
  width: 200px;
}
</style>