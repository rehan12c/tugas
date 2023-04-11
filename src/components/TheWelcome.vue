<template>
    <WelcomeItem>
        <div id="app">
    <router-view></router-view>
  </div>
  <h2 align="center">Login akun</h2>

  <center>
    <label for="usname">Username:</label>
    <input type="text" id="usname" name="usname"><br><br>
    <label for="password">Pasworrd:</label>
    <input type="text" id="Password" name="Password"><br><br>
    <input type="submit" value="Masuk">
  </center>
    </WelcomeItem>
</template>

<script>
import WelcomeItem from './WelcomeItem.vue';

export default {
    name: "Login.vue",
    components: { WelcomeItem }
}
</script>
