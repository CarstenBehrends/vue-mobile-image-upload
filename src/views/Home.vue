<template>
  <div class="home">
    <image-input>
      <div slot="activator">UPLOAD</div>
    </image-input>
  </div>
</template>



<script>
import ImageInput from "../components/ImageInput.vue";
// @ is an alias to /src

export default {
  name: "home",
  components: { ImageInput }
};
</script>
