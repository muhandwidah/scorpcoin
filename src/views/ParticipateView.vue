<template>
    <div align="center" justify="center">
        <div class="text-container">
            <h1>Participate</h1>
            <p id='title-subtext'>How to buy SCRP</p>
        </div>
        <v-divider id="divider"></v-divider>
        <div class="text-container2">
            <h1>Purchase SCRP with</h1>
        </div>
        <div class="card-container">
            <v-card class="mx-auto my-12" height="500" max-width="374">
                <v-app-bar absolute color="white" elevate-on-scroll scroll-target="#scrolling-techniques-7">
                    <h3>Buy SCRP</h3>
                    <v-spacer></v-spacer>
                    <v-app-bar-nav-icon></v-app-bar-nav-icon>
                </v-app-bar>
                <div class="moonpay-text-input" align="center" justify="center">
                    <v-text-field color="orange" label="I want to spend" outlined></v-text-field>
                    <v-text-field color="orange" label="You get" outlined></v-text-field>
                </div>

                <v-card-actions>
                    <v-btn block color="orange"><a id="btn-text">Continue</a></v-btn>
                </v-card-actions>
            </v-card>
            <p class="paragraph-subtext">The above widget is provided by a third party provider (MoonPay) and is not associated with Blue Scorpion</p>
        </div>
        <v-divider id="divider"></v-divider>
    </div>
</template>

<script>
export default {
    name: 'ParticipateView',
}
</script>

<style>
.moonpay-text-input{
    padding-top: 50%;
    width: 80%;
}
#moonpay-comp{
    padding-top: 50%;
}
#btn-text{
    color: white;
}
#moonpay-comp-text{
    margin: auto;
    font-family: 'Staatliches', cursive;
    color: black;
    font-size: 150%;
}
#moonpay-comp-btns{
    margin-top: 50%;
    font-family: 'Staatliches', cursive;
    color: black;
    font-size: 150%;
}
.paragraph-subtext{
    margin: 1.25%;
    font-family: 'Staatliches', cursive;
    color: black;
}
#title-subtext{
    margin: .25%;
    font-family: 'Staatliches', cursive;
    color: #717171;
}
.text-container{
    margin: 2.5%;
}
.text-container2{
    margin: .5%;
}
#divider{
    margin-top: 7.5%;
    margin-bottom: 7.5%;
    width: 85%;
    margin-left: auto;
    margin-right: auto;
}
</style>