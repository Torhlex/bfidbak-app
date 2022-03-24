<template>
  <div class="home">
    <Nav />
    <div class="flex flex-col justify-center items-center mt-12">
      <h1 class="text-white text-3xl md:leading-snug md:text-5xl">
        Welcome to Bfree <br />
        Escalation App <br />
        (BEA)
      </h1>
      <p class="mt-3 text-white leading-7 md:text-lg">
        BEA is for easy access to <br />
        feedback from the AMS to the <br />
        technical team in real time.
      </p>
    </div>
    <div class="flex justify-center items-center">
      <button
        class="text-indigo-500 mt-3 rounded bg-white flex justify-center items-center p-3 font-bold hover:bg-indigo-500 hover:text-white"
      >
        <router-link to="/signup"> Get started </router-link>
        <span>
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="h-5 w-5"
            viewBox="0 0 20 20"
            fill="currentColor"
          >
            <path
              fill-rule="evenodd"
              d="M7.293 14.707a1 1 0 010-1.414L10.586 10 7.293 6.707a1 1 0 011.414-1.414l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414 0z"
              clip-rule="evenodd"
            /></svg
        ></span>
      </button>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import Nav from "@/components/Nav.vue";

export default {
  name: "HomeView",
  components: {
    Nav,
  },
};
</script>
<style>
.home {
  background-image: url(../assets/pexels-karolina-grabowska-4194854\ 2.png);
  background-size: cover;
  text-align: center;
  width: 100%;
  height: 100vh;
}
</style>
