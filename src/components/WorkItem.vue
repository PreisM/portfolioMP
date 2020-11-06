<template>
  <article class="work-item">
    <img :src="img" />
    <div class="description">
      <h2>{{ title }}</h2>
      <h3>
        <a :href="live" target="_blank">Live</a>
        <a :href="code" target="_blank">Code</a>
      </h3>
    </div>
  </article>
</template>
       
<script>
export default {
  props: ["img", "title", "live", "code"]
};
</script>
