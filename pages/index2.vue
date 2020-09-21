<template>
    <span>
        <v-container>
            <span style="font-size:24px;" class="mdi mdi-chevron-left"></span>
            <v-icon style="margin-left: 280px; margin-top: -15px;">mdi-dots-vertical</v-icon>
        </v-container>
         <v-card style="background-color:#fff; color:#000; border-radius:10px 10px 0px 0px; margin-top:-10px; ">
            <v-container>
                <span style="font-size:24px; margin-right:5px;">Hi</span> <strong><span style="font-size:24px;">Vilma,</span></strong>
                <br>
                <span style="font-size:14px; color:#696969; margin-right:100px;">Total Balance</span>
                <span style="font-size:24px; color:#3CB371;">$23,452.³⁴</span>
                <br>
                <br>
                <v-card class="bg1">
                   <v-container>
                       <v-row>
                           <v-col sm-8>
                                <v-container>
                                    <span style="font-size:12px; color:#fff;">Total Balance</span>
                                    <h2>$1,452.³⁴</h2>
                                </v-container>
                           </v-col>
                           <v-col sm-4>
                                <v-container>
                                    <span style="font-size:40px; margin-left:20px;">|</span>
                                    <span style="font-size:24px; margin-left:10px;">Send</span>
                                </v-container>
                           </v-col>
                       </v-row>
                   </v-container>
                </v-card>
                    <br>
                <v-card class="bg1">
                   <v-container>
                       <v-row>
                           <v-col sm-8>
                                <v-container>
                                    <span style="font-size:12px; color:#fff;">Available balance</span>
                                    <h2>$577.⁴⁴</h2>
                                </v-container>
                           </v-col>
                           <v-col sm-4>
                                <v-container>
                                    <span style="font-size:40px; margin-left:20px;">|</span>
                                    <span style="font-size:24px; margin-left:10px;">Send</span>
                                </v-container>
                           </v-col>
                       </v-row>
                   </v-container>
                </v-card>
                <br>
                        <div style="text-align:center;">
                            <v-container>
                                <span style="color:#696969; font-size:20px;">Transactions</span><span style="color:#696969; margin-left:150px;" class="mdi mdi-arrow-down"></span>
                                <hr color="#58bf6b">
                                <span style="color:#696969; font-size:20px;">My Cards</span><span style="color:#696969; margin-left:180px;" class="mdi mdi-arrow-down"></span>
                                <hr color="#58bf6b">
                                <span style="color:#696969; font-size:20px;">Call Your bank</span><span style="color:#696969; margin-left:135px;" class="mdi mdi-arrow-down"></span>
                            </v-container>
                            
                        </div>

            </v-container>
        </v-card>

        <v-footer  :elevation="hover ? 26 : 6"
          style="padding-bottom:1px; background-color:#fff;">
            <v-row style="text-align:center;">
                <v-col cols="3">
                     <v-icon style="color:#696969;">mdi-home</v-icon>
                </v-col>
               <v-col cols="3">
                     <v-icon style="color:#696969;">mdi-account</v-icon>
                </v-col>
              <v-col cols="3">
                     <v-icon style="color:#696969;">mdi-email</v-icon>
                </v-col>
               <v-col cols="3">
                    <span style="font-size:20px; color:#696969;" class="mdi mdi-cash-usd"></span>
                </v-col>
            </v-row>
        </v-footer>
    </span>
    
        
</template>

<style scoped>
  .bg1 {
    background: linear-gradient(to bottom left, #46c1b4 20%, #50c193 40%, #58bf6b 85%);
    border-radius: 25px;
  }
</style>
