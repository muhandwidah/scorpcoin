<template>
    <div align="center" justify="center">
        <div class="text-container">
            <h1>Our Innovations</h1>
        </div>
        <v-divider id="divider"></v-divider>
        <div class="text-container">
            <h1>The X Factor</h1>
        </div>
        <div class="text-container">
            <p id='paragraph-subtext'>A review article published in the journal Nature in 2020 highlights the importance of inflammation in the pathogenesis of a wide range of chronic diseases, including cardiovascular disease, diabetes, cancer, and neurodegenerative disorders. <br> The authors state that chronic inflammation is a major driver of disease, and that targeting inflammation could be an effective strategy for preventing and treating many chronic diseases.</p>
            <p id='paragraph-subtext'>Chronic inflammation has been linked to a wide range of illnesses, including IBS, Crohn's disease, heart disease, and cancer.<br> According to a study by the Centers for Disease Control and Prevention, chronic diseases account for 6 out of 10 deaths in the United States each year, and inflammation is a significant contributor to the development and progression of these diseases.</p>
            <p id='paragraph-subtext'>This means 60% of our potential investors benefit directly from the treatments created by Dr. Mickalian, and close to 100% of our population have been touched by inflammation related disease from someone in their families or friend groups.</p>
            <p id='paragraph-subtext'>IBS, IBD and Crohn's disease are both inflammatory bowel diseases that affect the digestive tract. <br> According to the Crohn's & Colitis Foundation, approximately 1.6 million Americans have either Crohn's disease or ulcerative colitis.<br> According to a study published in the journal Gut in 2020, IBD affects around 0.5-1% of the population in Western countries.<br> Symptoms of IBD include diarrhea, abdominal pain, and weight loss. Current treatments for IBD include anti-inflammatory drugs, immunosuppressants, and biologic therapies.</p>
            <p id='paragraph-subtext'>Heart disease, another major contributor to chronic illness, is also linked to inflammation.<br> According to the American Heart Association, nearly half of all adults in the United States have some form of cardiovascular disease.<br> Chronic inflammation can lead to the buildup of plaque in the arteries, which can increase the risk of heart attack and stroke.</p>
            <p id='paragraph-subtext'>Cancer is also strongly associated with inflammation.<br> According to the American Cancer Society, inflammation can promote the growth and spread of cancer cells. Chronic inflammation is thought to contribute to the development of several types of cancer, including colorectal cancer, lung cancer, and liver cancer.<br> Current treatments for cancer include surgery, chemotherapy, and radiation therapy.</p>
            <p id='paragraph-subtext'>A study published in the journal Toxins in 2020 found that blue scorpion venom extract had significant anti-inflammatory effects in laboratory tests.<br> Another study published in the Journal of Venomous Animals and Toxins including Tropical Diseases in 2021 found that blue scorpion venom had cytotoxic effects on several types of cancer cells, suggesting its potential as a cancer treatment.</p>
            <p id='paragraph-subtext'>There is ongoing research into the potential therapeutic uses of blue scorpion venom for inflammatory diseases.<br> A study published in the journal Toxins in 2021 investigated the anti-inflammatory effects of blue scorpion venom on mice with induced colitis.<br> The researchers found that the venom reduced inflammation and improved the mice's symptoms.<br> However, more research is needed to determine the safety and efficacy of blue scorpion venom as a treatment for human inflammatory diseases.</p>
        </div>
        <v-divider id="divider2"></v-divider>
        <fourthComp/>
        <v-divider id="divider2"></v-divider>
    </div>
</template>

<script>
import fourthComp from '../components/fourthComp.vue'

export default {
    name: "InnovationView",
    components: {
        fourthComp,
    },
}
</script>

<style>
#title-subtext{
    margin: .25%;
    font-family: 'Staatliches', cursive;
    color: #717171;
}
.text-container{
    margin: 5vw;
    width: 80%;;
}
#paragraph-subtext{
    margin: 1.25%;
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
    margin-top: 7.5%;
    margin-bottom: 7.5%;
    width: 85%;
    margin-left: auto;
    margin-right: auto;
}
#divider2{
    margin-top: 5%;
    margin-bottom: 7.5%;
    width: 85%;
    margin-left: auto;
    margin-right: auto;
}
</style>