<template>
    <div align="center" justify="center">
        <div class="text-container">
            <h1>Join Our Community</h1>
        </div>
        <v-divider id="divider"></v-divider>
            <v-col align="center" justify="center">
                <img class="nft-card-image" src="../assets/images/nft-card-template.png">
            </v-col>
        <v-divider id="divider"></v-divider>
            <v-row>
                <div id="mint-btn" align="center" justify="center">
                    <v-btn block color="black" @click.stop="dialog = true"><h2 id="btn-text">Mint Now</h2></v-btn>
                    <v-dialog v-model="dialog" max-width="290">
                        <v-card>
                            <v-card-title>
                                <h2 id="dialog-title">Join The Community</h2>
                            </v-card-title>
                            <v-col align="center" justify="center">
                                <img class="nft-card-image" src="../assets/images/nft-card-template-single.png">
                            </v-col>
                            <v-col align="center" justify="center">
                                <v-btn class="web3-btns" color="#3999fc" block><h2 class="web3-btn-text">WalletConnect</h2> <img class="web3-logos" src="https://altcoinsbox.com/wp-content/uploads/2023/04/wallet-connect-logo.png"></v-btn>
                                <v-btn class="web3-btns" color="#f6851b" block><h2 class="web3-btn-text">MetaMask</h2> <img class="web3-logos" src="https://1000logos.net/wp-content/uploads/2022/05/MetaMask-Symbol.png"></v-btn>
                            </v-col>
                            <v-card-actions>
                                <v-spacer></v-spacer>
                                <v-btn color="red darken-1" text @click="dialog = false">Cancel</v-btn>
                            </v-card-actions>
                        </v-card>
                    </v-dialog>
                </div>
            </v-row>
        <v-divider id="divider"></v-divider>
        <div class="nft-text-container">
            <p class="nft-text">Join the SCRP community and take your involvement to the next level with our exclusive NFT. <br><br> This unique digital asset not only locks in a consistent price for the Blue Venom serum for a full year, but it also offers you early access to purchase the serum ahead of official sales. <br><br> But that's not all - as an NFT holder, you'll be invited to exclusive community events and enjoy substantial discounts on our products and services. <br><br> Don't miss out on this opportunity to deepen your engagement with the $SCRP community and maximize your benefits from our pioneering biotech project. <br><br> Secure your NFT today and be a part of the future of nutraceuticals.</p>
        </div>
        <v-divider id="divider"></v-divider>
    </div>
</template>

<script>
export default {
    name: "CommunityView",
    data () {
        return {
            dialog: false,
        }
    },

}
</script>

<style>
.web3-btn-text{
    color: white;
}
.web3-logos{
    max-width: 25px;
    margin: 1.5%;
}
.web3-btns{
    margin-top: 2.5%;
    margin-bottom: 2.5%;
}
#dialog-title{
    color: black;
    margin: auto;
}
#btn-text{
    color: white;
}
#mint-btn{
    width: 50%;
    height: auto;
    margin: auto;
    margin-top: 2.5vh;
    font-family: 'Staatliches', cursive;
}
h2{
    font-family: 'Staatliches', cursive;
}
.nft-card-image{
    aspect-ratio: 1/1;
    width: 60%;
    max-width: 25vw;
    height: auto;
}
.nft-text-container{
    margin: 5vw;
    width: 80%;
}
.nft-text{
    font-family: 'Staatliches', cursive;
    font-size: 115%;
}
#title-subtext{
    margin: .25%;
    font-family: 'Staatliches', cursive;
    color: #717171;
}
.text-container{
    margin: 2.5%;
}
#divider{
    margin-top: 7.5vh;
    margin-bottom: 7.5vh;
    width: 85%;
    margin-left: auto;
    margin-right: auto;
}
</style>