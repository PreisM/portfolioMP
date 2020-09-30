<template>
  <div id="about">
    <HomeLink />
    <div class="aboutHead">
      Are you looking for a Junior Frontend Developer?
      <p>
        <span class="blueCaption">Here </span>
        <span class="yellowCaption">I am</span>
      </p>
    </div>
    <div class="aboutBody">
      <h1>Hello!</h1>
      <p>Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet consectetur adipisicing elit. Obcaecati odio consequuntur pariatur natus ipsam quasi veniam mollitia voluptatum nulla? Vitae?</p>
      <div class="skill">
        <div class="space">
          <h2>What do I use on a daily basis</h2>
          <ul>
            <li>HTML</li>
            <li>CSS/SCSS</li>
            <li>Bootstrap</li>
            <li>Tailwind</li>
            <li>JavaScript</li>
            <li>jQuery</li>
            <li>VueJS</li>
            <li>Git</li>
            <li>Gulp</li>
            <li>Webpack</li>
            <li>restApi</li>
            <li>npm/Yarn</li>
            <li>VSC</li>
          </ul>
        </div>
        <div class="space">
          <h2>What do I use occasionally</h2>
          <ul>
            <li>VueX</li>
            <li>PHP</li>
            <li>MySQL</li>
            <li>Node.js</li>
            <li>AdobeXD</li>
            <li>Photoshop</li>
          </ul>
        </div>
      </div>
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
