<template>
<div>
  <section>
      <HeaderNavVue/>
  </section>

  <section>
      <TrustedCompaniesVue/>
  </section>

  <section class="section-1">
      <NftStartVue/>
  </section>

  <section class="section-2">
      <NftToolsVue/>
  </section>

  <section class="section-3">
      <MaqerPlaceVue/>
  </section>

  <section class="section-4">
      <DashboardVue/>
  </section>

  <section class="section-5">
      <ContactVue/>
  </section>

  <section class="section-6">
      <OthersUseCaseVue/>
  </section>

  <section class="section-7">
      <OpinionVue/>
  </section>

  <section>
      <FooterSection1Vue/>
  </section>

  <section>
      <FooterSection2Vue/>
  </section>

</div>
  
</template>

<script>
import ContactVue from './Contact.vue'
import DashboardVue from './Dashboard.vue'
import HeaderNavVue from './HeaderNav.vue'
import MaqerPlaceVue from './MaqerPlace.vue'
import NftStartVue from './NftStart.vue'
import NftToolsVue from './NftTools.vue'
import TrustedCompaniesVue from './TrustedCompanies.vue'
import OthersUseCaseVue from './OthersUseCase.vue'
import OpinionVue from './Opinion.vue'
import FooterSection1Vue from './FooterSection1.vue';
import FooterSection2Vue from './FooterSection2.vue'

export default {
  name: 'HelloWorld',
  components: {
     HeaderNavVue,
     TrustedCompaniesVue,
     NftStartVue,
     NftToolsVue,
     MaqerPlaceVue,
     DashboardVue,
     ContactVue,
     OthersUseCaseVue,
     OpinionVue,
     FooterSection1Vue,
     FooterSection2Vue
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.section-1{
    padding-top: 5rem;
}

.section-2 {
    padding-top: 6rem;
}

.section-3 {
    padding-top: 6rem;
}

.section-4 {
  padding-top: 6rem;
}

.section-5 {
  padding-top: 6rem;
}

.section-6 {
  padding-top: 6rem;
}

.section-7 {
  padding-top: 6rem;
  padding-bottom: 6rem;
}

</style>
