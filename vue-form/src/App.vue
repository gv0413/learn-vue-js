<template>
  <div>
    <tool-bar></tool-bar>
    <router-view></router-view>
    <!-- <form v-on:submit.prevent="submitForm">
      <div>
        <label for="username">id: </label>
        <input type="text" id="username" v-model="username">
      </div>
      <div>
        <label for="password">pw: </label>
        <input type="password" id="password" v-model="password">
      </div>
      <button type="submit" >login</button>
    </form> -->
  </div>
</template>

<script>
import ToolBar from './components/ToolBar.vue';
// import axios from 'axios';

export default {
  components: {
    ToolBar
  },
  // data: function() {
  //   return {
  //     username: '',
  //     password: '',
  //   }
  // },
  // methods: {
  //   submitForm: function() {
  //     // event.preventDefault(); //새로고침을 막아줌
  //     console.log(this.username, this.password);
  //     var url = 'https://jsonplaceholder.typicode.com/users';
  //     var data = {
  //       username: this.username,
  //       password: this.password
  //     }
  //     axios.post(url, data)
  //       .then(function(response) {
  //         console.log(response);
  //       })
  //       .catch(function(error){
  //         console.log(error);
  //       });
  //   }
  // },
}
</script>

<style>

</style>