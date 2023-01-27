<script setup>
import LikeSad from "./components/LikeSad.vue";
</script>

<template>
  <div>
    <section class="py-5">
      <div class="row py-lg-5">
        <h1 style="text-align: center">Wednesday</h1>
        <h4 style="text-align: center">
        </h4>
        <div class="containbutton">
          <button class="button3">Main call to action</button>
          <button class="button4">Secondary Action</button>
        </div>
      </div>
    </section>
    <div class="album py-5 bg-light">
      <div class="container">
        <div class="card" style="background-color: ">
          <img
            src="https://files.vogue.co.th/uploads/imagejenna.jpg"
            class="card-img-top"
            alt="..."
          />
          <div class="card-body">
            <h5 class="card-title">Wednesday</h5>
            <p class="card-text">
              Wednesday, the eldest daughter of the Addams family, 13, is obsessed with death and fun experiments that can be fatal.
            </p>
            <div class="d-flex justify-content-between align-items-center">
              <LikeSad></LikeSad>
              <small>9 mins</small>
            </div>
          </div>
        </div>
        <div class="card" style="background-color: ">
          <img
            src="https://files.vogue.co.th/uploads/imagejenna.jpg"
            class="card-img-top"
            alt="..."
          />
          <div class="card-body">
            <h5 class="card-title">Wednesday</h5>
            <p class="card-text">
              Wednesday, the eldest daughter of the Addams family, 13, is obsessed with death and fun experiments that can be fatal.
            </p>
            <div class="d-flex justify-content-between align-items-center">
              <LikeSad></LikeSad>
              <small>9 mins</small>
            </div>
          </div>
        </div>
        <div class="card" style="background-color: ">
          <img
            src="https://files.vogue.co.th/uploads/imagejenna.jpg"
            class="card-img-top"
            alt="..."
          />
          <div class="card-body">
            <h5 class="card-title">Wednesday</h5>
            <p class="card-text">
              Wednesday, the eldest daughter of the Addams family, 13, is obsessed with death and fun experiments that can be fatal.
            </p>
            <div class="d-flex justify-content-between align-items-center">
              <LikeSad></LikeSad>
              <small>9 mins</small>
            </div>
          </div>
        </div>
        <div class="card" style="background-color: ">
          <img
            src="https://files.vogue.co.th/uploads/imagejenna.jpg"
            class="card-img-top"
            alt="..."
          />
          <div class="card-body">
            <h5 class="card-title">Wednesday</h5>
            <p class="card-text">
              Wednesday, the eldest daughter of the Addams family, 13, is obsessed with death and fun experiments that can be fatal.
            </p>
            <div class="d-flex justify-content-between align-items-center">
              <LikeSad></LikeSad>
              <small>9 mins</small>
            </div>
          </div>
        </div>
        <div class="card" style="background-color: ">
          <img
            src="https://files.vogue.co.th/uploads/imagejenna.jpg"
            class="card-img-top"
            alt="..."
          />
          <div class="card-body">
            <h5 class="card-title">Wednesday</h5>
            <p class="card-text">
              Wednesday, the eldest daughter of the Addams family, 13, is obsessed with death and fun experiments that can be fatal.
            </p>
            <div class="d-flex justify-content-between align-items-center">
              <LikeSad></LikeSad>
              <small>9 mins</small>
            </div>
          </div>
        </div>
        <div class="card" style="background-color: ">
          <img
            src="https://files.vogue.co.th/uploads/imagejenna.jpg"
            class="card-img-top"
            alt="..."
          />
          <div class="card-body">
            <h5 class="card-title">Wednesday</h5>
            <p class="card-text">
              Wednesday, the eldest daughter of the Addams family, 13, is obsessed with death and fun experiments that can be fatal.
            </p>
            <div class="d-flex justify-content-between align-items-center">
              <LikeSad></LikeSad>
              <small>9 mins</small>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
h1 {
  color: rgb(0, 0, 0);
  text-align: center;
}
h4 {
  color: rgb(255, 205, 205);
  text-align: center;
}
.containbutton {
  display: grid;
  justify-content: center;
  padding-top: 20px;
  grid-template-columns: auto auto;
  column-gap: 10px;
}
.container {
  display: grid;
  justify-content: center;
  grid-template-columns: auto auto auto;
  row-gap: 20px;
  column-gap: 50px;
}
.card {
  width: 18rem;
  scroll-behavior: smooth;
}
.button3 {
  background-color: rgb(220, 194, 255);
  color: white;
  transition-duration: 0.3s;
}
.button3:hover {
  box-shadow: 0 0 3px 2px darkgray;
  background-color: rgb(0, 96, 255);
}
.button3:active {
  box-shadow: 0 0 4px 2px gray;
}
.button4 {
  background-color: darkgray;
  color: white;
  transition-duration: 0.3s;
}
.button4:hover {
  box-shadow: 0 0 3px 2px darkgray;
  background-color: gray;
}
.button4:active {
  box-shadow: 0 0 4px 2px gray;
}
</style>
