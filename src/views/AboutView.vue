<template>
    <div align="center" justify="center">
        <div>
            <div class="text-container">
                <h1>Mission</h1>
                <p id='faq-subtext'>In addition to providing stability to the cryptocurrency market, SCRP has a mission to promote the research and development for new peptide-based and biopharmaceutical treatments. <br> The venom of the blue scorpion has been shown to have potential applications in the treatment of a variety of medical conditions, including cancer, autoimmune diseases, and chronic pain. <br> By funding research and development, SCRP is helping to advance medical science and bring new treatments to those in need.</p>
            </div>
            <v-divider id="divider"></v-divider>
            <div class="timeline-container">
                <v-timeline>
                    <v-timeline-item color="black" small>
                        <template v-slot:opposite>
                        </template>
                        <div class="py-4">
                            <h2 id="timeline-title">Proceeds Goal</h2>
                            <div>
                                <p class="timeline-text">
                                    Proceeds from the sale of SCRP will also be used to fund habitat and ecosystem reclamation projects.<br><br> The harvesting of the venom is done in a sustainable manner that ensures the preservation of the natural environment, and expansion of the species. <br><br> By investing in SCRP, investors will be supporting efforts to preserve the natural world and protect endangered species.
                                </p>
                                </div>
                        </div>
                    </v-timeline-item>
                    <v-timeline-item color="black" small>
                        <template v-slot:opposite>
                        </template>
                        <div class="py-4">
                            <h2 id="timeline-title">Social Goal</h2>
                            <div>
                                <p class="timeline-text">
                                    Our social goal at SCRP is to support emerging economies, benefit community enrichment programs, and promote social responsibility in 3rd world countries. <br><br> The company will partner with local organizations to provide funding for education, healthcare, and other initiatives that benefit the community. <br><br> By investing in $SCRP, investors will be supporting a company that is committed to making a positive impact in the world.
                                </p>
                                </div>
                        </div>
                    </v-timeline-item>
                    <v-timeline-item color="black" small>
                        <template v-slot:opposite>
                        </template>
                        <div class="py-4">
                            <h2 id="timeline-title">Overall Goal</h2>
                            <div>
                                <p class="timeline-text">
                                    Overall, SCRP is a unique and innovative cryptocurrency that combines the stability of a physical commodity with a commitment to environmental and social responsibility. <br><br> By investing in SCRP, investors have an opportunity to support a company that is working to make a positive impact on the world while also potentially realizing significant financial returns.
                                </p>
                                </div>
                        </div>
                    </v-timeline-item>
                </v-timeline>
            </div>
            <v-divider id="divider"></v-divider>
            <v-row align="center" justify="center">
                <v-card shaped class="commodity-card">
                    <v-card-title><p class="commodity-card-title">What is a Commodity Coin?</p></v-card-title>
                    <v-divider></v-divider>
                    <v-col align="center" justify="center">
                        <p class="commodity-card-text">SCRP will be a commodity coin. <br> A cryptocurrency that is backed by a physical commodity, in our case Blue Scorpion Venom. <br> The idea behind commodity coins is to provide a stable store of value by tying the value of the cryptocurrency to the value of the underlying commodity.</p>
                    </v-col>
                </v-card>
                <v-card color="#F5F5F5" elevation="1" :img="require('../assets/images/btc-rocket.png')" shaped class="commodity-card">
                </v-card>
            </v-row>
            <v-row align="center" justify="center">
                <v-card color="#F5F5F5" elevation="1" :img="require('../assets/images/gold-investment.png')" shaped class="commodity-card">
                </v-card>
                <v-card shaped class="commodity-card">
                    <v-card-title><p class="commodity-card-title">Why is this stable?</p></v-card-title>
                    <v-divider></v-divider>
                    <v-col align="center" justify="center">
                        <p class="commodity-card-text">For Example, A gold-backed cryptocurrency would be pegged to the value of gold. <br> So, if the price of gold goes up, the value of the cryptocurrency would go up as well. <br> This can provide a hedge against inflation and market volatility, as the value of the commodity is likely to remain relatively stable over time.</p>
                    </v-col>
                </v-card>
            </v-row>
            <v-row align="center" justify="center">
                <v-card shaped class="commodity-card">
                    <v-card-title><p class="commodity-card-title">How is this secure?</p></v-card-title>
                    <v-divider></v-divider>
                    <v-col align="center" justify="center">
                        <p class="commodity-card-text">Commodity coins are created using blockchain technology, which provides a secure and transparent way to track the ownership and transfer of the coins. <br> This can make commodity coins an attractive investment option for those looking for a more stable alternative to traditional cryptocurrencies, which can be subject to wild price swings.</p>
                    </v-col>
                </v-card>
                <v-card color="#F5F5F5" elevation="1" :img="require('../assets/images/blockchain-technology.png')" shaped class="commodity-card">
                </v-card>
            </v-row>
            <v-divider id="divider"></v-divider>
        </div>

        <div class="table-container">
            <div class="text-container">
                <h1>The Future of Commodities</h1>
                <p id='faq-subtext'>A cryptocurrency that is backed by Carribean Blue Scorpion Venom, the most expensive liquid on earth at $39 million dollars a gallon. <br> The mission of the $SCRP team is to provide stability to the cryptocurrency market by utilizing physical reserves of the venom to secure value. <br> The rarity of the venom, coupled with the difficulty in harvesting, ensures that the value of $SCRP will remain stable over time. <br> By creating a cryptocurrency backed by a physical commodity, our coin provides investors with a secure and transparent investment opportunity.</p>
            </div>
            <v-divider id="divider"></v-divider>
            <v-simple-table>
                <template v-slot:default>
                    <thead>
                        <tr>
                            <th class="text-left">Venom Reserve</th>
                            <th class="text-left">1/4 Gal</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>$9,750,000.00</td>
                            <td></td>
                        </tr>
                    </tbody>
                    <thead>
                        <tr>
                            <th class="text-left">Coin Total Options</th>
                            <th class="text-left">Value</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr v-for="data in coinValueData" :key="data">
                            <td>{{ data.CTO }}</td>
                            <td>{{ data.value }}</td>
                        </tr>
                    </tbody>
                </template>
            </v-simple-table>
        </div>
        <a id="whitepaper-text">Read Our Whitepaper</a>
        <v-divider id="divider"></v-divider>
    </div>
</template>

<script>
export default {
    name: 'AboutView',
    data () {
        return {
            coinValueData: [
            {
                CTO: '30,000,000',
                value: '0.356',
            },
            {
                CTO: '60,000,000',
                value: '0.1528',
            },
            {
                CTO: '120,000,000',
                value: '0.0764',
            },
            {
                CTO: '250,000,000',
                value: '0.0382',
            },
            {
                CTO: '500,000,000',
                value: '0.0191',
            },
            {
                CTO: '1,000,000,000',
                value: '0.00975',
            },
            ],
        }
        },
}
</script>

<style>

#whitepaper-text{
    font-family: 'Staatliches', cursive;
}
.timeline-text{
    width: 80%;
    font-family: 'Staatliches', cursive;
}
#timeline-title{
    font-family: 'Staatliches', cursive;
}
.commodity-card{
    width: 450px;
    aspect-ratio: 4/3;
    max-width: 450px;
    margin: 1.5%;
}
.commodity-card-title{
    margin: auto;
    margin-top: 5%;
    font-family: 'Staatliches', cursive;
    color: black;
    font-size: 105%;
    text-align: center;
}
.commodity-card-text{
    margin: 5%;
    margin-top: 1.5%;
    font-family: 'Staatliches', cursive;
    color: #717171;
    font-size: 125%;
    text-align: center;
}
.table-container{
    margin: 2.5%;
    width: 65%;
}
.timeline-container{
    margin: 2.5%;
    width: 65%;
}
#faq-subtext{
    margin: .25%;
    font-family: 'Staatliches', cursive;
    color: #717171;
}
.text-container{
    margin: 2.5%;
}
#divider{
    margin-top: 7.5%;
    margin-bottom: 7.5%;
    width: 85%;
    margin-left: auto;
    margin-right: auto;
}
</style>