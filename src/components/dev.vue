<template>
  <div>
      
         <h1>DEVELOPERS:</h1>
 
      <template v-for="(dev, index) in devs">
          <developer :key="index" :name="dev.name" :image="dev.image"
           :description="dev.description"></developer>
      </template>
    
  </div>
</template>
<script>
import developer from "./developer.vue";
export default {
  name: "dev",
  data() {
    return {
      devs: [
        {
          name: "Irish Rufo",
          image: require("@/assets/josephine.jpg"),
          description: "Back end I"
        },
        {
          name: "Josephine Morre",
          image: require("@/assets/josephine.jpg"),
          description: "Back end II"
        },
        {
          name: "Patrick Cabi-an",
          image: require("@/assets/patrice.jpg"),
          description: "Project manager"
        },
        {
          name: "Jerome Burce",
          image: require("@/assets/patrice.jpg"),
          description: "front end II"
        }
      ]
    };
  },
  components: {
    developer
  }
};
</script>