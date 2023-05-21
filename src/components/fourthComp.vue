<template>
        <v-container>
            <v-row>
                <v-col align="center" justify="center" class="leftContainer">
                    <v-col class="innerContainer">
                        <v-card class="graphic-card" elevation="5" shaped :img="require('../assets/images/doctors-graphic.png')">
                        </v-card>
                    </v-col>
                </v-col>
                <v-col align="center" justify="center" class="leftContainer">
                    <v-col class="innerContainer">
                        <v-card  class="graphic-card" elevation="5" shaped :img="require('../assets/images/research-graphic.png')">
                        </v-card>
                    </v-col>
                </v-col>
                <v-col align="center" justify="center" class="leftContainer">
                    <v-col class="innerContainer">
                        <v-card  class="graphic-card" elevation="5" shaped :img="require('../assets/images/healthcare-graphic.png')">
                        </v-card>
                    </v-col>
                </v-col>
                <v-col align="center" justify="center" class="leftContainer">
                    <v-col class="innerContainer">
                        <v-card  class="graphic-card" elevation="5" shaped :img="require('../assets/images/research-graphic2.png')">
                        </v-card>
                    </v-col>
                </v-col>
            </v-row>
        </v-container>
</template>

<script>
export default {
    name: "fourthComp",
}
</script>

<style>
.graphic-card{
    aspect-ratio: 4/3;
    height: auto;
    width: 100%;
}
.innerButton{
    margin: 10px;
}
.innerText{
    color: white;
}
.leftContainer{
    width: 50%;
    height: 100%;
    left: 0;
}
.rightContainer{
    width: 50%;
    height: 100%;
    right: 0;
}
.innerContainer{
    margin-top: 25%;
    margin-bottom: 25%;
    padding: 5%;
    max-width: 550px;
}
</style>