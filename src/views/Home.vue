<template>
  <div id="home">
  <div id="navigation">
    <div class="text" :class="{ 'mobileText':mobile}">
      Hello.
      <router-link to="/about" :class="{ 'mobileLink':mobile}">About</router-link>
    </div>
    <div class="text blue" :class="{ 'mobileText':mobile }">
      I am
      <router-link to="/works" :class="{ 'mobileLink':mobile }">Works</router-link>
    </div>
    <div class="text yellow" :class="{ 'mobileText':mobile }">
      Maciej
      <router-link to="/contact" :class="{ 'mobileLink':mobile }">Contact</router-link>
    </div>

  </div>
    <img src="../img/logoMP.png">
    <button id="mobileBtn" @click="mobileTap()">
      Tap me!
    </button>
  </div>
</template>

<script>

export default {
  name: "Home",
  components: {},
  data() {
    return {
      mobile: false
    };
  },
  methods: {
    mobileTap() {
      this.mobile = !this.mobile;
    }
  }
};
</script>
