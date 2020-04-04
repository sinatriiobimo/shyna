<template>
  <div class="home">
    <HeaderShyna></HeaderShyna>
    <HeroShyna></HeroShyna>
    <WomenShyna></WomenShyna>
    <InstaShyna></InstaShyna>
    <PartnerShyna></PartnerShyna>
    <FooterShyna></FooterShyna>
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderShyna from "../components/HeaderShyna";
import HeroShyna from "../components/HeroShyna";
import WomenShyna from "../components/WomenShyna";
import InstaShyna from "../components/InstaShyna";
import PartnerShyna from "../components/PartnerShyna";
import FooterShyna from "../components/FooterShyna";

export default {
  name: "Home",
  components: {
    HeaderShyna,
    HeroShyna,
    WomenShyna,
    InstaShyna,
    PartnerShyna,
    FooterShyna
  }
};
</script>
