<template>
  <div class="text-center mt-4">
    <br><br>
    <img src="~/assets/newlogo.png">
    <b-container class="grid">
      <nuxt-link to="/login">
        <br>
        <br>
        <br>
        <br>
        <b-button
          size="lg"
          variant="dark"
        >
          Login
        </b-button>
      </nuxt-link>
    </b-container>
  </div>
</template>

<script>
export default {};
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