<template>
  <div id="home">
      <div class="text" v-if="seen">Hello.
        <router-link to="/about">About</router-link>
      </div>
      <div class="text blue" v-if="seen">I am
        <router-link to="/works">Works</router-link>
      </div>
      <div class="text yellow" v-if="seen">Maciej
        <router-link to="/contact">Contact</router-link>
      </div>
      <!-- <img src="../img/logo.png"> -->
      <button class="mobile" v-on:click="seen = !seen">
        Tap me!
      </button>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "Home",
  components: {
    // HelloWorld
  },
  data () {
    return {
      seen: true
    }
  }
};
</script>

<style>

  </style>