<template>
  <section class="container">
    <div>
      <Applogo />
      <h1 class="title">
        nuxt-twitter-auth
      </h1>
      <h2 class="subtitle">
        Nuxt.js project
      </h2>
      <TwitterLogin />
      <div class="links">
        <a
          href="http://127.0.0.1:3000/server/auth/twitter"
          class="button--grey">Twitter Login</a>
      </div>
    </div>
  </section>
</template>

<script>

</script>

<style>
.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}
.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}
.links {
  padding-top: 15px;
}
</style>
