<template>
  <div>
    And this is the axios component
    <div class="container">
      <div class="row">
        <div class="col-12">Call status: {{ AxiosCall }}</div>
      </div>
    </div>
  </div>
</template>

<script>
import axios from "axios";

export default {
  name: "AxiosComponent",
  data() {
    return {
      AxiosCall: "",
    };
  },
  methods: {
    UpdateAxiosCall: function () {
      this.AxiosCall = "Actualizado";
      console.log("Hola");
    },
  },
  created() {},
  mounted() {
    axios
      .get("http://jsonplaceholder.typicode.com/posts", {
        params: {
          //ID: 12345
        },
      })
      .then((response) => {
        console.log(response);
        this.AxiosCall = "updated";
      })
      .catch(function (error) {
        console.log(error);
      })
      .then(function () {
        // always executed
      });
  },
};
</script>

<style scoped>
</style>