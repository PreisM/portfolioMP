<template>
  <div id="contact">
    <HomeLink />
    <div class="contactHead">
      Let's make something
      <span class="blueCaption">good</span>.
      <p class="yellowCaption">Together.</p>
    </div>
    <div class="contactBody">
      <p>
        <a
          class="social"
          href="https://www.facebook.com/preis.maciej"
          target="_blank"
          >Facebook</a
        >
      </p>
      <p>
        <a
          class="social"
          href="https://www.linkedin.com/in/maciej-preis-31476b19a/"
          target="_blank"
          >Linkedin</a
        >
      </p>
      <p>
        <a class="social" href="https://github.com/PreisM" target="_blank"
          >Github</a
        >
      </p>
      <p>
        <a class="social" href="mailto:maciej.preis@onet.eu" target="_blank"
          >maciej.preis@onet.eu</a
        >
      </p>
    </div>
  </div>
</template>

<script>
import HomeLink from "../components/HomeLink";

export default {
  components: {
    HomeLink
  }
};
</script>
