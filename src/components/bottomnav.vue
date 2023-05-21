<template>
    <div>
        <v-row>
        </v-row>
        <div align="center" justify="center" class="button-container">

            <v-btn href="/about" class="footer-btn" text color="black">About</v-btn>
            <v-btn class="footer-btn" text color="black">Privacy Policy</v-btn>
            <v-btn class="footer-btn" text color="black">Licensing</v-btn>
            <v-btn href="/contact"  class="footer-btn" text color="black">Contact</v-btn>
        </div>

        <div class="absolute-bottom-text" align="center" justify="center">
            <span class="text-sm text-gray-500 sm:text-center dark:text-gray-400">© 2023 <a href="https://bluescorpion.com/" class="reserved-text">Blue Scorpion™</a> All Rights Reserved.
            </span>
        </div>
    </div>
</template>


<!-- <divider id="divider"></divider> -->
<script>
export default {
    name: 'BottomNavComp',

}
</script>

<style>

.reserved-text{
    text-decoration: none;
}
.absolute-bottom-text{
    margin-top: 1%;
    margin-bottom: 1.5%;

}
.footer-btn{
    margin-left: 1.5%;
    margin-right: 1.5%;
    font-family: 'Staatliches', cursive;
    font-size: 150%;
}
.footer-text{
    font-family: 'Staatliches', cursive;
    font-size: 115%;
    text-decoration: none;
}
.logo-container{
    max-width: 150px;
    margin-left: 2.5%;
}
.button-container{
    margin: auto;
}
#divider{
    margin-top: 5%;
    margin-bottom: 5%;
    width: 85%;
    margin-left: auto;
    margin-right: auto;
}
</style>