<template>
  <div class="home">
    hello Rubick
    <button id="showNotification">通知</button>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "Home",
  // components: {
  //   HelloWorld,
  // },
  mounted() {
    document
      .getElementById("showNotification")
      .addEventListener("click", () => {
        window.showNotification();
      });
  },
};
</script>
