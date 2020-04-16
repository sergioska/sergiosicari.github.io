<template>
  <div class="container">
    <div>
      <logo />
      <h1 class="title">
        Sergio Sicari
      </h1>
      <h2 class="subtitle">
        Software engineer with several year of experience in software development, mainly in PHP stack
      </h2>
      <div>
        <a href="https://www.linkedin.com/sergiosicari" target="_blank" class="social">
          <font-awesome-icon :icon="['fab', 'linkedin']" size="2x"/>
        </a>
        <a href="https://github.com/sergioska" target="_blank" class="social">
          <font-awesome-icon :icon="['fab', 'github']" size="2x"/>
        </a>
        <a href="https://twitter.com/sergioska" target="_blank" class="social">
          <font-awesome-icon :icon="['fab', 'twitter']" size="2x"/>
        </a>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import Logo from '~/components/Logo.vue'

export default Vue.extend({
  components: {
    Logo
  }
})
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #212529;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #212529;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}

a.social {
  color: #212529;
  text-decoration: none;
  padding: 10px;
}

a.social:link {
  color: #212529;
  text-decoration: none;
  padding: 10px;
}

a.social:visited {
  color: #212529;
  text-decoration: none;
  padding: 10px;
}

a.social:hover {
  color: #212529;
  text-decoration: none;
  padding: 10px;
}
</style>
