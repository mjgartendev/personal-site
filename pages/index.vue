<template>
  <section class="container">
    <div>
      <app-logo/>
      <h1 class="title">
        Michael J. Garten
      </h1>
      <h2 class="subtitle">
        Full stack web developer
      </h2>
      <div class="links">
        <a
          href="https://www.linkedin.com/in/mjgarten"
          target="_blank"
          class="button--green">LinkedIn</a>
        <a
          href="https://github.com/mjgartendev"
          target="_blank"
          class="button--grey">GitHub</a>
      </div>
    </div>
  </section>
</template>

<script>
import AppLogo from '~/components/AppLogo.vue'

export default {
  components: {
    AppLogo
  }
}
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
  font-size: 80px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 32px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
