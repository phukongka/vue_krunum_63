<template>
  <div style="margin-top:-30px;" class="bg2">
    <v-container>
      <center><img style="padding-top:50px;" src="Untitled-1.png" width="120px"></center>

      <h1 style="text-align:center; padding-top:40px;">Welcome to the</h1>
      <h1 style="text-align:center;">Bank of the future</h1>
      <center><span style="font-size:14px;">Create your new Wallet.</span></center>
    
      <center><v-btn @click="linkindex1" rounded color="#fff" dark style="color:#58bf6a; margin-top:80px;">Get Started</v-btn></center>

      <br><br><br><br><br>
       <center><span style="font-size:14px;">Already have an account? Sing in</span></center>
    </v-container>
  </div>
</template>

<style>
    .bg2 {
        background-image: url('../static/dollar.png');
        background-size: 480px;
    }
</style>

<script>
export default {
   methods: {
    linkindex1() {
      this.$router.push('/index1')
    },
  }
}
</script>

