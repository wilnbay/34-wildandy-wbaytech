<template>
    <v-container class="bodywork">
        <div class="testi-1">
        <v-row>
            <v-col lg="6">
                <h2>What we've <br>
                    worked on</h2>
            </v-col>
            <v-col lg="6">
                <img   width="492px" height="492px" src="./../assets/testi-1.png" alt="">
         
                    <p class="subheading1">Rey technology</p>
                    <p class="subheading2">Logo design , branding , web development</p>
             
            </v-col>
        </v-row>
        </div>

        <div class="testi-2">
             <v-row>
            <v-col lg="6">
                <img   width="492px" height="492px" src="./../assets/testi-2.png" alt="">
         
                    <p class="subheading1">Mam bakery</p>
                    <p class="subheading2">Logo design , branding , web development</p>
            </v-col>
        </v-row> 
        </div>

        <div class="testi-3">
             <v-row>
            <v-col lg="6">
               
            </v-col>
            <v-col lg="6">
             <img   width="492px" height="492px" src="./../assets/testi-3.png" alt="">
         
                    <p class="subheading1">idgaf co</p>
                    <p class="subheading2">uiux, branding , web development</p>
             
            </v-col>
        </v-row>
        </div>
    </v-container>
    
</template>

<script> 
    export default {};
</script>

<style>

.bodywork{
    margin-top: 75px;
    
}
.testi-2 {
     position: relative;
    margin-top: -250px;
    margin-left: 10;
}
.testi-3{
      position: relative;
    margin-top: -250px;
    margin-left: 10;
}
h2{
    font-size: 45px;
    line-height: 65px;
    font-family: poppins;
    font-weight: 800;
}
p.subheading1{
    margin-top: 20px;
    font-weight: 700;
    font-size: 32px;
    font-family: poppins;
}
p.subheading2{
    font-weight: 400;
    font-size: 20px;
    font-family: poppins;
}


</style>