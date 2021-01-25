<template>
  <div class="about">
    <!-- <h1>This is an about page</h1> </h1>-->
    <Mycanvas />
  </div>
</template>

<script>
// @ is an alias to /src
import Mycanvas from "@/components/MyCanvas.vue";

export default {
  name: "About",
  components: {
    Mycanvas,
  },
};
</script>
