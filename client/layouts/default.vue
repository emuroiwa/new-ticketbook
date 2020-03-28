<template>
  <div>
    <top-nav />
    <nuxt/>
    <tb-footer />
  </div>
</template>

<script>
import TopNav from "./partials/TopNav";
import TbFooter from "~/components/general/tb-footer.vue";

export default {
  components: {
    TopNav,
    TbFooter
  }
};
</script>
