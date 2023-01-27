<script setup>
    import { ref } from 'vue';
const like = ref(0);
const sad = ref(0);

function likeClick(){
  like.value++;
}

function sadClick(){
  sad.value++;
}

</script>

<template>
  <div>
    <button @click="likeClick">Like</button>
                  like = {{ like }}
                  <button @click="sadClick">Sad</button>
                  sad = {{ sad }}
    <big style="margin: 10px">{{ like }}</big>
    
  </div>
</template>

<style scoped>
.button {
  background-color: rgb(239, 255, 239);
  transition-duration: 0.3s;
}
.button:hover {
  box-shadow: 0 0 3px 2px darkgray;
  background-color: rgb(0, 224, 0);
}
.button:active {
  box-shadow: 0 0 4px 2px gray;
}
.button2 {
  background-color: rgb(255, 221, 221);
  transition-duration: 0.3s;
}
.button2:hover {
  box-shadow: 0 0 3px 2px darkgray;
  background-color: rgb(255, 233, 233);
}
.button2:active {
  box-shadow: 0 0 4px 2px gray;
}
</style>

