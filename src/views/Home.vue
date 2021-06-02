<template>
  <div class="container">
    <div class="form">
      <form action="" method="post">
        <h2 class="title">Sign in</h2>
        <div class="input-field">
          <i class="mdi mdi-account"></i>
          <input type="text" placeholder="Username" />
        </div>
        <div class="input-field">
          <i class="mdi mdi-lock"></i>
          <input type="password" placeholder="Password" />
        </div>
        <input type="submit" value="Login" class="btn solid" />
        <p class="social-text">Or sign in with social platforms</p>
        <div class="social-media">
          <a href="#" class="social-icon">
            <i class="fab mdi mdi-facebook"></i>
          </a>
          <a href="#" class="social-icon">
            <i class="fab mdi mdi-twitter"></i>
          </a>
          <a href="#" class="social-icon">
            <i class="fab mdi mdi-instagram"></i>
          </a>
          <a href="#" class="social-icon">
            <i class="fab mdi mdi-linkedin"></i>
          </a>
        </div>
      </form>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'Home',
  components: {},
  data() {
    return {};
  },
};
</script>

<style lang="scss"></style>
