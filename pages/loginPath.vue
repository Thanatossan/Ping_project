<template>
  <div>
    <navbar />
    <div class="text-center mt-4">
      <br><br>
      <img
        src="~/assets/logo2.png"
        width="700px"
      >
      <br><br><br>
      <b-container>
        <nuxt-link to="/service">
          <b-button
            variant="dark"
            class='m-5 p-4'
            size="lg"
          >
            Service
          </b-button>
        </nuxt-link>
        <nuxt-link to="/private">
          <b-button
            variant="dark"
            class='m-5 p-4'
            size="lg"
          >
            Private
          </b-button>
        </nuxt-link>
      </b-container>
    </div>
  </div>
</template>

<script>
import navbar from "../components/navbar";
export default {
  components: {
    navbar
  }
};
</script>

<style>
.grid {
  display: grid;
  grid-template-columns: [xl-start] 1fr 1.5rem [md-start] minmax(0, 624px) [md-end] 1.5rem 1fr [xl-end];
}

.grid * {
  grid-column: md;
}
.grid-xl {
  grid-column: xl;
}
.center {
  margin: auto;
  width: 50%;
  padding: 10px;
}
</style>