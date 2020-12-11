<template>
  <div>
    This is the Axios View
    <div class="container">
      <div class="row">
        <div class="col-12">
          <AxiosComponent></AxiosComponent>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import AxiosComponent from "../components/AxiosComponent";
export default {
  name: "Axios",
  components: {
    AxiosComponent,
  },
};
</script>

<style scoped>
</style>