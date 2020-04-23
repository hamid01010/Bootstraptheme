<template>
  <div class="home">
    <jumbotron-section /><br><br>
    <hr>
    <card-section />
    <hr>
    <video-section />
    <hr>
    <carousel />
    <hr>
    <gallary />
    <hr>
    <mini-carousel />
    <hr>
  </div>
</template>

<script>
import JumbotronSection from "../components/JumbotronSection"
import CardSection from "../components/CardSection"
import VideoSection from "../components/VideoSection"
import Carousel from "../components/Carousel"
import Gallary from "../components/Gallary"
import MiniCarousel from "../components/MiniCarousel"

export default {
  name: 'Home',
  components: {
      JumbotronSection,
      CardSection,
      VideoSection,
      Carousel,
      Gallary,
      MiniCarousel
  }
}
</script>
