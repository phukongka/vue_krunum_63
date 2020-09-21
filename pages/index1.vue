<template>
    <div class="bg2">
        <v-container>
            <div style="margin-top:20px;">
                <h1 style="text-align:center;">Create your</h1>
                <h1 style="text-align:center;">new wallet</h1>
                <center><span style="font-size: 11px;">Lorem Ipsum is simply dummy text of the printing and typesetting industry. 
                Lorem Ipsum</span></center>
                <br>
                  <v-text-field label="E-mail" outlined dense></v-text-field>
                  <v-text-field type="password" label="Password" outlined dense></v-text-field>
                  &nbsp; &nbsp; &nbsp;&nbsp;&nbsp;<input type="checkbox"> <span style="font-size: 13px;">Remember</span>
                  <span style="font-size: 13px; margin-left:75px;">Forget Password</span>
            </div>
                <center><v-btn rounded color="#fff" dark style="color:#58bf6a; margin-top:40px; margin-bottom:10px;">Create Account</v-btn></center>
                <center><span style="font-size: 13px;">Sign up with</span></center>
                <center><span style="font-size:42px;" class="mdi mdi-facebook"></span></center>
                <br>
                <center><span style="font-size:14px;">Already have an account? Sing in</span></center>
        </v-container>
    </div>
</template>

<style>
    .bg2 {
        background-image: url('../static/dollar.png');
        background-size: 480px;
        position: absolute;
    }
</style>
