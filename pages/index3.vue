<template>
    <div>
        <v-container>
            <span style="font-size:24px;" class="mdi mdi-chevron-left"></span>
            <v-icon style="margin-left: 280px; margin-top: -15px;">mdi-dots-vertical</v-icon>
            <h2 style="margin-left:20px;">Your Balance</h2>
            <span style="font-size:14px; margin-left:20px;">In this card</span>

             <h2 style="margin-left:190px;">$23,452.³⁴</h2>
        </v-container>
    <br>
        <v-card style="background-color:#fff; color:#000; border-radius:20px 20px 0px 0px; margin-top:5px; ">
            <v-container>  
                <v-row>
                    <v-col cols="9">
                        <v-card style="border-radius:15px; background-color:#58bf6b;" class="bg2">
                            <v-container>
                                <span style="font-size:18px;">Vilma Carter</span> <strong><span style="font-size:20px; margin-left:70px;">VISA</span></strong> 
                                <span style="font-size:14px;">Krungthai</span>
                                <br><br><br>
                                <span style="font-size:14px;">KRUNGTHAI SHOP SMART</span><br>
                                <span style="font-size:20px;">**** ***** ***** 2580</span>
                            </v-container>
                        </v-card>
                    </v-col>
                    <v-col cols="3">
                        <h1 style="margin-top:50px; margin-left:5px; color:#58bf6b " class="mdi mdi-credit-card-plus"></h1>
                        <h2 style="font-size:10px; margin-top:-10px; color:#696969;">add-card</h2>
                    </v-col>
                </v-row>

                <br>

                    <div style="text-align:center;">
                            <v-container>
                                <span style="color:#696969; font-size:20px;">Card Info</span><span style="color:#696969; margin-left:150px;" class="mdi mdi-arrow-down"></span>
                                <hr color="#58bf6b">
                                <span style="color:#696969; font-size:18px;">Consultation & policy</span><span style="color:#696969; margin-left:65px;" class="mdi mdi-arrow-down"></span>
                                <hr color="#58bf6b">
                                <span style="color:#696969; font-size:20px;">Transfer</span><span style="color:#696969; margin-left:160px;" class="mdi mdi-arrow-down"></span>
                            <br>
                            <br>
                            <br>
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
    </div>
    
        
</template>

<style scoped>
  .bg1 {
    background: linear-gradient(to bottom left, #46c1b4 20%, #50c193 40%, #58bf6b 85%);
    border-radius: 25px;
  }
</style>
<style>
    .bg2 {
        background-image: url('../static/dollar.png');
        background-size: 100%;
    }
</style>
