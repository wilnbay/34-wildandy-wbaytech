<template>
    <v-container >
        <v-row >
            <v-col lg="12" class="subtitle">
            <h2>How we work</h2>
            </v-col>
        </v-row>

        <v-row class="card">
            <v-col lg="4">
            <v-img width="143px" height="143px"  src="./../assets/icon-1.png" alt=""></v-img>
             <div class="my-4 text-subtitle-1">
                <h3>Strategy</h3>
                 <v-list-item-title>We take the time to ask the <br>
            right questions from the start.  <br>
            Winning products start here.
            </v-list-item-title>
            <li>Product strategy</li>
            <li>Existing product audit</li>
            <li>Design workshops</li>
            </div>
         
            </v-col>

            <v-col lg="4">
            <v-img width="143px" height="143px"  src="./../assets/icon-2.png" alt=""></v-img>
             <div class="my-4 text-subtitle-1">
                <h3>Branding</h3>
                 <v-list-item-title>We take the time to ask the <br>
            right questions from the start.  <br>
            Winning products start here.
            </v-list-item-title>    
              <li>Brand identity</li>
            <li>Logo</li>
            <li>Photo/Video</li>
            </div>
            </v-col>


             <v-col lg="4" d-f>
            <v-img width="143px" height="143px"  src="./../assets/icon-3.png" alt=""></v-img>
             <div class="my-4 ">
                <h3>production</h3>
                 <v-list-item-title class="text-1">We take the time to ask the <br>
            right questions from the start.  <br>
            Winning products start here.
            </v-list-item-title>
            <li> UX/UI</li>
            <li>Social media campaigns</li>
            <li>Design system</li>
            </div>
         
            </v-col>

        </v-row>
    </v-container>
</template>

<script> 
    export default {};
</script>

<style>
.subtitle{
    margin-top: 75px;
}
.card{
    margin-top: 35px;
    margin-bottom: 100px;
}
h2{
    font-size: 45px;
    line-height: 65px;
    font-family: poppins;
    font-weight: 800;
}

h3{
    font-size: 32px;
    line-height: 43px;
    font-family: poppins;
    font-weight: 600;
}

.card{
    margin-top: 150px;
    margin-left: 50px;
}
</style>