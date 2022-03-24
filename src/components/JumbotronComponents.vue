<template>
   <v-container >
       <v-row pt="1">
           <v-col lg="6">
               <h1 class="intro-text ">Designing Your Digital  <br>
                    Products For Better  <br>
                User Experience.</h1>
                <p class="deskripsi">We help companies to create <br> 
                    experiences for their users, from the <br>
                    initial idea to the final product.</p>
                <v-btn rounded color="black" dark  elevation="7" height="56" width="181"  class="btn-hero" href="FormComponents.vue">Contact Us</v-btn>
           </v-col> 

           <v-col lg="6">
               <v-img class="gambaratas" width="100%"  src="./../assets/header.png" alt=""></v-img>
           </v-col>
       </v-row>
    
   </v-container>
</template>

<script>
export default {};
</script>

<style scoped>
    h1.intro-text{
        margin-top: 100px;
        font-size: 45px;
        font-weight:800;
        line-height: 55px;
        font-family: poppins;
        color: black;
    }
    .gambaratas{
        margin-top: -50px;
    }
    p.deskripsi{
        font-size: 24px;
        font-weight:400;
        font-family: poppins;
        line-height: 35px;
        color: black;
        margin-top: 28px;
    }
    .btn-hero{
        margin-top: 10px;
    }

    
</style>