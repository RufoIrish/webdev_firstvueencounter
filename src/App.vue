<template>
  <div >
   
    <div  style="background-image : url('https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcQtA-KDfsMlF6pqxUTQSdNLTVC4YvvgkXDXcP0poZcFZN9iGN9d')">
     <center>
        <h1>EcoGreen</h1>
        <!-- <my-header></my-header> -->
        <nav>
          <router-link to="/">Home</router-link>&nbsp;
          <router-link to="./about">About</router-link>
        </nav>
        <hr/>
      </center>
    </div>
      <center>
        <my-home></my-home>
        <router-view></router-view>
    </center>

  </div>
</template>

<script>

export default {
  name: 'app'
};
</script>

<style>
* {
  box-sizing: border-box;
  margin: 0;
}
</style>
