<template>
            <v-row align="center" justify="center">
                <div align="center" justify="center" class="side-Container">
                    <v-card elevation="1">
                        <v-card-text>
                            <div id="text-container" class="text--primary card-text">
                                Dive into SCRP, a digital asset anchored by blue scorpion venom.<br><br> Your investment signifies a stake in our innovative biotech journey and supports global conservation efforts.
                            </div>
                        </v-card-text>
                    </v-card>
                </div>
                <div align="center" justify="center" class="middle-card">
                        <v-card id="card-inside" rounded elevation="5">
                            <v-card-text>
                                <div>
                                    <img id="scorp-exchange-image" src="../assets/images/scorp-exchange.png">
                                </div>
                                <div id="text-container" class="card-text">
                                    Ready to tap into the potential of blue scorpion venom?<br><br> Start your investment journey with SCRP today
                                </div>
                                <div class="btnContainer">
                                    <v-btn href="/participate" x-large id="getStartedBtn" class="innerBtn" elevation="0" color="black" block><a id="getStartedBtnText">Purchase Now</a></v-btn>
                                </div>
                            </v-card-text>
                        </v-card>
                    </div>
                    <div id="right-container" align="center" justify="center" class="side-Container">
                        <v-card elevation="1">
                            <v-card-text>
                                <div id="text-container" class="text--primary card-text">
                                    Join the biotech future with SCRP, more than just a coin. <br><br> Investing in SCRP fosters life-saving research and promotes sustainable health initiatives globally.
                                </div>
                            </v-card-text>
                        </v-card>
                    </div>
            </v-row>
</template>

<script>
export default {
    name: "thirdComp",
}
</script>

<style>
#side-Container{

}
#text-container{
    font-size: 150%;
}

#card-title{
    font-size: large;
}
.card-text{
    font-family: 'Staatliches', cursive;
    margin: 2.5%;
    color: black;
}
#card-inside{
    padding: 5%;
    max-width: 21em;

}
#scorp-exchange-image{
    aspect-ratio: 1/1;
    max-width: 100px;
}
#middle-card{
    z-index: 5;
    aspect-ratio: 1/1;
    box-shadow: 15 15 35px red;

}
.side-Container{
    max-width: 15em;
    margin: 2.5%;
    color: #F5F5F5;
}
</style>