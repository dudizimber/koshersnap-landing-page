<template>
  <div class="body">
    <img class="logo" alt="Kosher Snap logo" src="./assets/hand.svg" />
    <div class="text">
      <img alt="Kosher" src="./assets/kosher.svg" />
      <img alt="Snap" src="./assets/snap.svg" />
    </div>
    <h2>Coming soon...</h2>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "App",
  components: {},
});
</script>

<style lang="scss">
body {
  margin: 0;
  padding: 0;
  background-color: #5127c7;
  color: white;
  font-family: 'Nunito', 'Roboto', sans-serif, Arial, Helvetica;
}

.body {
  width: 100vw;
  height: 100vh;
  overflow: hidden;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  text-align: center;
}

.logo {
  max-width: 500px;
  min-width: 250px;
  margin-bottom: 32px;
}

.text {
  display: flex;
  align-items: center;

  :last-child {
    margin-top: 31px;
    margin-left: 8px;
  }
}

</style>
