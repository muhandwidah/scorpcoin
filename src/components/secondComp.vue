<template>
        <v-row class="mainContainer" align="center" justify="center" >
            <div align="left" justify="center" class="text-Container">
                <v-col align="center" justify="center">
                    <h3 class="inner-item1">invest in a currency backed by an extraordinary natural resource - blue scorpion venom. <br><br> By tying digital assets to this life-changing commodity, we offer a stable investment opportunity that supports our mission to promote health, environmental conservation, and social responsibility.</h3>
                    <v-col align="center" justify="center" class="btnContainer">
                        <v-btn href="/community" block id="getStartedBtn2" class="innerBtn" elevation="0" color="black"><a id="getStartedBtnText2">Get started with scrp</a></v-btn>
                    </v-col>
                </v-col>


            </div>
            <div align="center" justify="center" class="coin-Container">
                    <div class="coin copper"></div>
            </div>
        </v-row>
</template>

<script>
export default {
    name: "secondComp",
}
</script>

<style>

.inner-item1{
    color: black;
    font-family: 'Staatliches', cursive;
    width: 22rem;
    margin: 2.5%;
    text-align: center;
}
.text-Container{
    text-align: left;
    width: 25rem;
    margin-left: auto;
    margin-right: 5%;
}
.coin-Container{
    margin-right: auto;
    margin-left: 5%;
}
.mainContainer{
    margin-top: 10%;
}
.getStartedBtn2{
    margin: auto;
}
#getStartedBtnText2{
    font-size: 110%;
    color: white;
    font-family: 'Staatliches', cursive;
}

:root {
--lowlight: #111;
--side: #717171;
--side-dark: #120e08;
--coin-size: 22rem;
--coin-face: url('https://i.ibb.co/hHCkf8x/Untitled-design.png');
}

.coin {
height: var(--coin-size);
width: var(--coin-size);
margin: 0.5rem;
display: flex;
flex-direction: column;
justify-content: center;
align-items: center;
}

.coin::before {
content: '';
display: block;
position: relative;
height: var(--coin-size);
width: var(--coin-size);
border-radius: 50%;
background-color: var(--face);
animation: spin 1.75s linear infinite;
background-image: var(--coin-face);
background-size: 100% 100%;
background-position: center;
background-blend-mode: overlay;
}

.coin.flip::before {
animation-name: flip;
}

.coin.copper::before {
filter:
    hue-rotate(-40deg)
    brightness(0.75)
    contrast(115%);
    animation-delay: -.25s;
}

/* animation definitions */

@keyframes spin {
0% {
    width: var(--coin-size);
    box-shadow:
    0 0 0 var(--side-dark);
    animation-timing-function: ease-in;
}

49.999% {
    width: 0.1rem;
    box-shadow:
    0.05rem 0 0 var(--side),
    0.1rem 0 0 var(--side),
    0.15rem 0 0 var(--side),
    0.2rem 0 0 var(--side),
    0.25rem 0 0 var(--side),
    0.3rem 0 0 var(--side),
    0.35rem 0 0 var(--side),
    0.4rem 0 0 var(--side),
    0.45rem 0 0 var(--side),
    0.5rem 0 0 var(--side),
    0.55rem 0 0 var(--side),
    0.6rem 0 0 var(--side),
    0.65rem 0 0 var(--side),
    0.7rem 0 0 var(--side),
    0.75rem 0 0 var(--side);
    transform: translateX(-0.375rem);
    background-color: var(--lowlight);
    animation-timing-function: linear;
}

50.001% {
    width: 0.1rem;
    box-shadow:
    -0.05rem 0 0 var(--side),
    -0.1rem 0 0 var(--side),
    -0.15rem 0 0 var(--side),
    -0.2rem 0 0 var(--side),
    -0.25rem 0 0 var(--side),
    -0.3rem 0 0 var(--side),
    -0.35rem 0 0 var(--side),
    -0.4rem 0 0 var(--side),
    -0.45rem 0 0 var(--side),
    -0.5rem 0 0 var(--side),
    -0.55rem 0 0 var(--side),
    -0.6rem 0 0 var(--side),
    -0.65rem 0 0 var(--side),
    -0.7rem 0 0 var(--side),
    -0.75rem 0 0 var(--side);
    transform: translateX(0.375rem);
    background-color: var(--lowlight);
    animation-timing-function: ease-out;
}

100% {
    width: var(--coin-size);
    box-shadow:
    0 0 0 var(--side-dark);
}
}

@keyframes flip {
0% {
    height: var(--coin-size);
    box-shadow:
    0 0 0 var(--side-dark);
    animation-timing-function: ease-in;
}

49.999% {
    height: 0.1rem;
    box-shadow:
    0 0.05rem 0 var(--side),
    0 0.1rem 0 var(--side),
    0 0.15rem 0 var(--side),
    0 0.2rem 0 var(--side),
    0 0.25rem 0 var(--side),
    0 0.3rem 0 var(--side),
    0 0.35rem 0 var(--side),
    0 0.4rem 0 var(--side),
    0 0.45rem 0 var(--side),
    0 0.5rem 0 var(--side),
    0 0.55rem 0 var(--side),
    0 0.6rem 0 var(--side),
    0 0.65rem 0 var(--side),
    0 0.7rem 0 var(--side),
    0 0.75rem 0 var(--side);
    transform: translateY(-0.375rem);
    background-color: var(--lowlight);
    animation-timing-function: linear;
}

50.001% {
    height: 0.1rem;
    box-shadow:
    0 -0.05rem 0 var(--side),
    0 -0.1rem 0 var(--side),
    0 -0.15rem 0 var(--side),
    0 -0.2rem 0 var(--side),
    0 -0.25rem 0 var(--side),
    0 -0.3rem 0 var(--side),
    0 -0.35rem 0 var(--side),
    0 -0.4rem 0 var(--side),
    0 -0.45rem 0 var(--side),
    0 -0.5rem 0 var(--side),
    0 -0.55rem 0 var(--side),
    0 -0.6rem 0 var(--side),
    0 -0.65rem 0 var(--side),
    0 -0.7rem 0 var(--side),
    0 -0.75rem 0 var(--side);
    transform: translateY(0.375rem);
    background-color: var(--lowlight);
    animation-timing-function: ease-out;
}

100% {
    height: var(--coin-size);
    box-shadow:
    0 0 0 var(--side-dark);
}
}

@keyframes gradientAnimation {
    0%{background-position:0% 55%}
    50%{background-position:100% 46%}
    100%{background-position:0% 55%}
}

</style>