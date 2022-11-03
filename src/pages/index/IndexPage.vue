<template>
  <q-page class="row">
    <div class="col-md-3 col-12 column">
      <IndexPageLeftSide />
    </div>
    <div class="col-md-6 col-12 column">
      <IndexPageMainTop />
      <IndexPageMainBottom />
    </div>
    <div class="col-md-3 col-12 column">
      <IndexPageRightSide />
    </div>
  </q-page>
</template>

<script>
import { defineComponent } from "vue";
import IndexPageLeftSide from "./IndexPageLeftSide.vue";
import IndexPageMainBottom from "./IndexPageMainBottom.vue";
import IndexPageMainTop from "./IndexPageMainTop.vue";
import IndexPageRightSide from "./IndexPageRightSide.vue";

export default defineComponent({
  name: "IndexPage",

  components: {
    IndexPageLeftSide,
    IndexPageRightSide,
    IndexPageMainBottom,
    IndexPageMainTop
  }
});
</script>
