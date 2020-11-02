<template>
  <div id="works">
    <HomeLink />
    <div class="worksHead">
      <span>Some of my works.</span>
      <p>
        <span class="blueCaption">Feel free</span>
        <span class="yellowCaption"> to check!</span>
      </p>
    </div>
    <div class="worksBody">
      <section class="workItems">
        <WorkItem
          v-for="work in works"
          :key="work.id"
          :img="work.img"
          :title="work.title"
          :live="work.live"
          :code="work.code"
        />
      </section>
    </div>
  </div>
</template>

<script>
import HomeLink from "../components/HomeLink";
import WorkItem from "../components/WorkItem";

export default {
  components: {
    HomeLink,
    WorkItem
  },
  data() {
    return {
      works: [
        {
          id: "1",
          img: require("@/img/burger.png"),
          title: "Burger Restaurant",
          live: "https://preism.github.io/BurgerRestaurant/",
          code: "https://github.com/PreisM/BurgerRestaurant"
        },
        {
          id: "2",
          img: require("@/img/invoiceapp.png"),
          title: "Invoice App",
          live: "https://preism.github.io/InvoiceApp/",
          code: "https://github.com/PreisM/InvoiceApp"
        },
        {
          id: "3",
          img: require("@/img/quiz.png"),
          title: "Quiz IT",
          live: "https://preism.github.io/QuizIT/",
          code: "https://github.com/PreisM/QuizIT"
        },
        {
          id: "4",
          img: require("@/img/calculator.png"),
          title: "Calculator",
          live: "https://preism.github.io/Calculator/",
          code: "https://github.com/PreisM/Calculator"
        },
        {
          id: "5",
          img: require("@/img/oldportfolio.png"),
          title: "Portfolio (out of date)",
          live: "https://preism.github.io/Portfolio/",
          code: "https://github.com/PreisM/Portfolio"
        },
        {
          id: "6",
          img: require("@/img/homergame.png"),
          title: "'The simpsons' game",
          live: "https://preism.github.io/HomerGame/",
          code: "https://github.com/PreisM/HomerGame"
        }
      ]
    };
  }
};
</script>

