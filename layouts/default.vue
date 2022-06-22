<template>
  <div class="ld">
    <!-- <nuxt-link to="/users">Users</nuxt-link>
    <nuxt-link to="/admin">Admin</nuxt-link>
    <nuxt-link to="/teacher">Teacher</nuxt-link>
    <nuxt-link to="/students">Students</nuxt-link>
    <nuxt-link to="/customer">Customer</nuxt-link>
     -->

    <Header />

    <Nuxt />
  </div>
</template>
<script>
import Header from "~/components/Header";
export default {
  components: {
    Header,
  },
};
</script>

<style >
.ld {
  background-color: aqua;
  margin: 0px;
}
</style>