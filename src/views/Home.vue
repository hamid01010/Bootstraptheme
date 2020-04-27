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
    <status />
    <hr>
    <blog-section />
    <email-section />
  </div>
</template>

<script>
import BlogSection from "../components/BlogSection"
import JumbotronSection from "../components/JumbotronSection"
import CardSection from "../components/CardSection"
import VideoSection from "../components/VideoSection"
import Carousel from "../components/Carousel"
import Gallary from "../components/Gallary"
import MiniCarousel from "../components/MiniCarousel"
import Status from "../components/Status"
import EmailSection from "../components/EmailSection"
export default {
  name: 'Home',
  components: {
      JumbotronSection,
      CardSection,
      VideoSection,
      Carousel,
      Gallary,
      MiniCarousel,
      Status,
      BlogSection,
      EmailSection
  }
}
</script>
