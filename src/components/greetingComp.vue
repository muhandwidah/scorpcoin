<template>
    <v-row align="center" justify="center">
        <div>
            <v-col align="center" justify="center">
                <img id="scorpion-image" class="fade-in" src="../assets/images/scorpion-web.png">
            </v-col>
        </div>
        <div class="right-container fade-in">
            <div class="textContainer" id="textContainer1">
                <h1 class="inner-items">Harness the Power of Blue Scorpion Venom</h1>
            </div>
            <div class="textContainer" id="textContainer2">
                <h3 class="inner-items"><br>A digital asset anchored by the value of polarized blue scorpion venom, represents a unique investment in the future of peptide-based treatments. <br><br> Experience potential appreciation, gain access to cutting-edge therapies, and contribute to global conservation efforts with every coin held.<br></h3>
            </div>
            <div class="btnContainer">
                <v-btn href="/community" id="getStartedBtn" class="innerBtn" elevation="0" color="black"><a id="getStartedBtnText">Get started with scrp</a></v-btn>
                <v-btn href="/participate" class="innerBtn" outlined ><a id="purchaseBtnText">Purchase scrp</a></v-btn>
            </div>
        </div>

    </v-row>
</template>

<script>
export default {
    name: "greetingComp",
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Staatliches&display=swap');
.fade-in {
	opacity: 1;
	animation-name: fadeInOpacity;
	animation-iteration-count: 1;
	animation-timing-function: ease-in;
	animation-duration: .75s;
}

@keyframes fadeInOpacity {
	0% {
		opacity: 0;
	}
    50% {
		opacity: 0.5;
	}
	100% {
		opacity: 1;
	}
}
#scorpion-image{
    aspect-ratio: 1/1;
    max-width: 325px;
    height: auto;
    margin: 2.5%
}
.divider{
    position: relative;
    border-left: 2px solid #717171;
    height: 500px;
    z-index: 5;
    margin: auto;
}
#getStartedBtnText{
    font-family: 'Staatliches', cursive;
    color: white;
}
#purchaseBtnText{
    font-family: 'Staatliches', cursive;
    color: black;
}
#getStartedBtn{
    margin-right: 15px;
}
#textContainer1{
    text-align: left;
    width: 17rem;
}
#textContainer2{
    text-align: left;
    width: 22rem;
}
.right-container{
    margin: 2.5%;
    aspect-ratio: 1/1;
    max-width: 325px;
}
h1{
    font-family: 'Staatliches', cursive;
}
h3{
    font-family: 'Staatliches', cursive;
}
.innerBtn{
    margin-top: 20px;
}
</style>