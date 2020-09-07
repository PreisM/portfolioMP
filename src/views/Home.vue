<template>
  <div id="home">
    <div class="text">Hello.
      <router-link to="/about">About</router-link>
    </div>
    <div class="text blue">I am
      <router-link to="/works">Works
      </router-link>
    </div>
    <div class="text yellow">Maciej
      <router-link to="/contact">Contact
      </router-link>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "Home",
  components: {
    // HelloWorld
  }
};
</script>
