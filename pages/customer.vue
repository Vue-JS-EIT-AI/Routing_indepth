<template>
  <div>
    
    <nuxt-child/>
    <h1>Let's fetch The users</h1>
    <input type="text"  v-model="userId"/>
    <button @click="OnLoadUser">Load User</button>
    {{userId}}

    <ul>
      <li>customer use 2 index one in 'customer' folder and one named 'customer.vue'</li>
      <li>So we use the root custom.vue and added the folder index as a child</li>
      <li><b>We used validation if someone use 'integer' it's fine . if use 'string ' then no page using regular expression</b></li>

    </ul>
  </div>
</template>

<script>
export default {
  data() {
    return {
      userId: "",
    };
  },
  methods:{
    OnLoadUser(){
        this.$router.push('/customer/' + this.userId)

    }
  }
};
</script>