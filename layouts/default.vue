<template>
  <div>
    <header class="hero">
      <h1 class="text-white text-2xl font-bold">Tim Jones</h1>
      <ul class="flex justify-between text-white menu">
        <li>BLOG</li>
        <li>PORTFOLIO</li>
        <li>GET IN TOUCH</li>
      </ul>
    </header>
    <Nuxt />
  </div>
</template>

<script>
export default {

}
</script>

<style>
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

.hero {
  display: flex;
  justify-content: space-between;
  width: 100%;
  height: 15rem;
  background-image: url(../static/code.jpg);
  background-color: rgba(49, 49, 49, 0.8);
  background-blend-mode: multiply;
  padding: 1rem 1rem;
}

ul.menu li {
  padding: 0rem 1rem;
}

</style>
