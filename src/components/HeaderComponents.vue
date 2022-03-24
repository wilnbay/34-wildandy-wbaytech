<template>
   <v-container>
       <v-app-bar  app color="#FFFFFF" black flat class="px-16">
       <v-title  bold ><h1>Wbaytech</h1></v-title>
        <v-spacer/>
    <v-btn class="btn-atas" text @click="scroll('home')"><strong>home</strong></v-btn>
    <v-btn text @click="scroll('project')"><strong>project</strong></v-btn>
    <v-btn text @click="scroll('about')"><strong>about</strong></v-btn>
    <v-btn text @click="scroll('contact')"><strong>contact us</strong></v-btn>
       </v-app-bar>
   </v-container>
</template>

<script> 
    export default {};
</script>

<style>
.logotext{
    font-weight: 800;
    font-size: 25px;
    font-family: poppins;
    margin-top: -30px;
}
 h1{
        
        font-size: 26px;
        font-weight:800;
        font-family: poppins;
        color: black;
    }


</style>