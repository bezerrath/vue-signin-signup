<template>
  <router-view />
</template>

<style lang="scss">
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

body,
input {
  font-family: 'Open Sans';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
.container {
  position: relative;
  width: 100%;
  min-height: 100vh;
  background-color: white;
}
.form {
  position: absolute;
  width: 100%;
  height: 100%;
  top: 0;
  left: 0;
}
form {
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
}
.title {
  font-size: 2.2rem;
  color: #2c3e50;
  margin-bottom: 0.5em;
}
.input-field {
  max-width: 380px;
  width: 100%;
  height: 55px;
  margin: $gap 0;
  background-color: #f3f3f3;
  border-radius: 55px;
  display: grid;
  grid-template-columns: 15% 85%;
  padding: 0 0.4rem;
}
.input-field i {
  text-align: center;
  line-height: 55px;
  color: #acacac;
  font-size: 1.1rem;
}
.input-field input {
  background: none;
  border: none;
  outline: none;
  line-height: 1;
  font-weight: 600;
  font-size: 1.1rem;
  color: #333;
}
.input-field input::placeholder {
  color: #aaa;
  font-weight: 500;
}
.btn {
  width: 150px;
  height: 49px;
  border: none;
  outline: none;
  border-radius: 49px;
  cursor: pointer;
  background-color: #5995fd;
  color: white;
  text-transform: uppercase;
  font-weight: 600;
  margin: 10px 0;
  transition: 0.3s;
}
.btn:hover {
  background-color: #4d84e2;
}
.social-text {
  padding: 0.7rem 0;
  font-size: 1rem;
}
.social-media {
  display: flex;
  justify-content: center;
}
.social-icon {
  height: 46px;
  width: 46px;
  border: 1px solid #333;
  margin: 0 0.45rem;
  display: flex;
  align-items: center;
  justify-content: center;
  text-decoration: none;
  color: #333;
  font-size: 1.1rem;
  border-radius: 50%;
  transition: 0.3s;
}
.social-icon:hover {
  color: #4481eb;
  border-color: #4481eb;
}
</style>
