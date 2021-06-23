<template>
  <div class="home">
    <HeaderDieqy />
    <SectionDieqy />
    <BannerDieqy />
    <InstaDieqy />
    <PartnerDieqy />
    <FooterDieqy />
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderDieqy from '@/components/HeaderDieqy.vue';
import SectionDieqy from '@/components/SectionDieqy.vue';
import BannerDieqy from '@/components/BannerDieqy.vue';
import InstaDieqy from '@/components/InstaDieqy.vue';
import PartnerDieqy from '@/components/PartnerDieqy.vue';
import FooterDieqy from '@/components/FooterDieqy.vue';

export default {
  name: 'Home',
  components: {
    HeaderDieqy,
    SectionDieqy,
    BannerDieqy,
    InstaDieqy,
    PartnerDieqy,
    FooterDieqy
  }
}
</script>
