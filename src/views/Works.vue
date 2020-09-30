<template>
    <div id="works">
      <HomeLink />
      <div class="worksHead">
        Here are my works. 
        <p> <span class="blueCaption">Feel free</span>  
        <span class="yellowCaption"> to check!</span></p>
      </div>
      <ul class="worksBody">
        <li class="portfolio-item">
          <img src="../img/burger.png" alt="BurgerMAXX">
          <div class="description">
            <h2>Burger Restaurant</h2>
            <h3><a href="https://preism.github.io/BurgerRestaurant/" target="_blank">Live</a> <a href="https://github.com/PreisM/BurgerRestaurant" target="_blank">Code</a></h3>
          </div>
        </li>
        <li class="portfolio-item">
          <img src="../img/invoiceapp.png" alt="InvoiceApp">
          <div class="description">
            <h2>Invoice App</h2>
            <h3><a href="https://preism.github.io/InvoiceApp/" target="_blank">Live</a> <a href="https://github.com/PreisM/InvoiceApp" target="_blank">Code</a></h3>
          </div>
        </li>
        <li class="portfolio-item">
          <img src="../img/quiz.png" alt="Quiz IT">
          <div class="description">
            <h2>Quiz IT</h2>
            <h3><a href="https://preism.github.io/QuizIT/" target="_blank">Live</a> <a href="https://github.com/PreisM/QuizIT" target="_blank">Code</a></h3>
          </div>
        </li>
        <li class="portfolio-item">
          <img src="../img/calculator.png" alt="Calculator">
          <div class="description">
            <h2>Calculator</h2>
            <h3><a href="https://preism.github.io/Calculator/" target="_blank">Live</a> <a href="https://github.com/PreisM/Calculator" target="_blank">Code</a></h3>
          </div>
        </li>
        <li class="portfolio-item">
          <img src="../img/oldportfolio.png" alt="Portfolio(outOfDate)">
          <div class="description">
            <h2>Portfolio (out of date)</h2>
            <h3><a href="https://preism.github.io/Portfolio/" target="_blank">Live</a> <a href="https://github.com/PreisM/Portfolio" target="_blank">Code</a></h3>
          </div>
        </li>
        <li class="portfolio-item">
          <img src="../img/homergame.png" alt="HomerGame">
          <div class="description">
            <h2>"The simpsons" game</h2>
            <h3><a href="https://preism.github.io/HomerGame/" target="_blank">Live</a> <a href="https://github.com/PreisM/HomerGame" target="_blank">Code</a></h3>
          </div>
        </li>
      </ul>
    </div>
</template>

<script>
import HomeLink from '../components/HomeLink'
export default {
  components: {
    HomeLink,
  }
}
</script>

