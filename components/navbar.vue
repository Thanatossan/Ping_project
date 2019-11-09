<template>
  <div>
    <link
      rel="stylesheet"
      href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css"
      integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T"
      crossorigin="anonymous"
    >
    <link
      rel="stylesheet"
      href="https://use.fontawesome.com/releases/v5.11.2/css/all.css"
    >

    <b-navbar
      toggleable="lg"
      type="dark"
      variant="dark"
      fixed="top"
    >
      <i class="fas fa-home white mr-2 ml-2"></i>
      <b-navbar-brand>Kingkran Wihala</b-navbar-brand>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse
        id="nav-collapse"
        is-nav
      >

        <!-- Right aligned nav items -->
        <b-navbar-nav class="ml-auto">
          <!-- Using 'button-content' slot -->
          <b-navbar-nav class="ml-auto">
            <p class="pt-2 white mr-2"> จำนวนการล็อคอิน : {{ $store.state.counter }} </p>
            <nuxt-link to="/">
              <b-button>Sign Out </b-button>
            </nuxt-link>
            <b-nav-item-dropdown
              right
              size="lg"
            >
              <!-- Using 'button-content' slot -->
              <template v-slot:button-content>
                <em>Contact Us</em>
              </template>

              <p class="p-2"> E-mail : Abdul.team@gmail.com
                Phone : 053-555789</p>

            </b-nav-item-dropdown>
          </b-navbar-nav>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<script>
export default {};
</script>

<style>
.white {
  color: #fff;
}
.white-bg {
  background: #fff;
}
.logo {
  width: 10%;
}
</style>