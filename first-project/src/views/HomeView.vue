<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <TodoItem />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
import TodoItem from "@/components/TodoItem.vue";

export default {
  name: "HomeView",
  components: {
    HelloWorld,
    TodoItem,
  },
};
</script>
