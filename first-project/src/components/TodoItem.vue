<template>
  <div>
    <!-- Iteration 1-->
    <h1>Es un componente nuevo</h1>
    <!-- Iteration 2-->
    <p>{{ hello }}</p>
    <button @click="helloworld">Click to say hello!</button>
  </div>
</template>

<script>
export default {
  name: "TodoItem",
  data() {
    return {
      hello: "Mensaje a cambiar",
    };
  },
  methods: {
    helloworld() {
      this.hello = "HelloWorld!";
    },
  },
};
</script>
