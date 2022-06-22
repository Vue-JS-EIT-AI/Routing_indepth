<template>
  <div>
    <h1>Student</h1>
    <input type="text" v-model="name" />
    <button @click="OnBtnClick">Add Student</button>
    {{ name }}
    <p> No validation string or number(any)</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      name: "",
    };
  },
  methods: {
    OnBtnClick() {
        this.$router.push('/students/'+this.name)
    },
  },
};
</script>