<template>
      <v-container >
        <v-row >
            <v-col lg="12">
            <h2>About Us</h2>
            </v-col>

             <v-col lg="12">
            <h3>We help promote the business of <br>
            entrepreneurs in Indonesia through <br>
            the right branding, by combining the <br>
            business and emotional aspects.</h3>
            </v-col>
            <v-col lg="12">
                <v-img width="100%" height="100%"  src="./../assets/about.png" alt=""></v-img>
            </v-col>

            <v-col lg="12">
                <v-img width="100%" height="100%"  src="./../assets/promosi.png" alt=""></v-img>
                 
            </v-col>
            <v-col cols="12">
                  <v-btn rounded color="black" dark   height="56" width="181"  class="btn-bawah">
                    Contact us 
                  </v-btn>
                </v-col>
        </v-row>
      </v-container>
</template>

<script> 
    export default {};
</script>

<style>
h2{
    font-size: 45px;
    line-height: 65px;
    font-family: poppins;
    font-weight: 800;
}

h3{
    font-size: 40px;
    line-height: 43px;
    font-family: poppins;
    font-weight: 600;
    margin-bottom: 48px;
}
.btn-bawah{
    position: relative;
    margin-left: 450px;
   margin-top: -200px;

}
</style>