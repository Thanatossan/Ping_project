<template>
  <div class="container grid center">
    <img
      src="~/assets/lock.png"
      class="center"
      width="50px"
    >
    <b-form
      @submit="onSubmit"
      v-if="show"
    >
      <b-form-input
        v-model="form.name"
        type="text"
        class="mt-5"
        required
        placeholder="Username"
      ></b-form-input>
      <b-form-input
        v-model="form.password"
        type="password"
        class="mt-3"
        required
        placeholder="Enter password"
      ></b-form-input>
      <b-button
        block
        type="submit"
        variant="dark"
        class="mt-3"
      >Submit</b-button>
    </b-form>
  </div>
</template>

<script>
export default {
  data() {
    return {
      form: {
        name: "",
        password: ""
      },
      show: true
    };
  },
  methods: {
    onSubmit(evt) {
      evt.preventDefault();
      if (
        this.form.name === "kingkarn_wihala@elearning.cmu.ac.th" &&
        this.form.password === "1234"
      ) {
        this.$store.commit("increment");
        this.$router.push("/loginPath");
      } else {
        alert("Email or password incorrect");
      }
    },
    onReset(evt) {
      evt.preventDefault();
      // Reset our form values
      this.form.name = "";
      this.form.password = "";
      // Trick to reset/clear native browser form validation state
      this.show = false;
      this.$nextTick(() => {
        this.show = true;
      });
    }
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
