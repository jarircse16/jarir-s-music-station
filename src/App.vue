<template>
  <div id="app">
    <AudioPlayer />
    <div class="footer">
    <p :style="{ color: 'white', textAlign: 'center', fontFamily:'Arial' }">&copy; 2023 Jarir's Music Station. Created by Vue.Js</p> <!-- Footer text goes here -->
    </div>
  </div>
</template>

<script>
import AudioPlayer from "./components/AudioPlayer.vue";

export default {
  components: {
    AudioPlayer,
  },
};
</script>
<style>
h1{
  color: red;
}
</style>
