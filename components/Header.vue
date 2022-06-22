<template>
  <div>
    <header class="header">
      <ul class="nav-items">
         <li>
          <nuxt-link to="/">Home</nuxt-link>
        </li>
        <li>
          <nuxt-link to="/users">Users</nuxt-link>
        </li>
        <li><nuxt-link to="/admin">Admin</nuxt-link></li>
        <li><nuxt-link to="/teacher">Teacher</nuxt-link></li>

        <li><nuxt-link to="/students">Students</nuxt-link></li>
        <li><nuxt-link to="/customer">Customer</nuxt-link></li>
      </ul>
      <!-- <p>asda</p> -->
    </header>
  </div>
</template>

<style scoped>
.header {
  width: 100%;
  height: 60px;
  background-color: rgb(199, 199, 137);
  display: flex;
  justify-content: center;
  align-items: center;
}
.nav-items {
  list-style: none;
  display: flex;
  justify-content: space-between;
  align-items: center;
  width:20%;
}
a{
  text-decoration: none;
}
a:hover{
  color: black;
  border: 1px solid;
}
</style>