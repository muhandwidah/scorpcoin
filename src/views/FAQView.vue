<template>
    <div align="center" justify="center">
        <div class="text-container">
            <h1>FAQ</h1>
            <p id='faq-subtext'>Frequently Asked Questions About SCRP</p>
        </div>
        <v-divider id="divider"></v-divider>
        <div class="expansion-container" justify="center">
            <v-expansion-panels inset>
            <v-expansion-panel v-for="i in faqitem" :key="i">
                <v-expansion-panel-header><p id='faq-subtext2'>{{i.question}}</p></v-expansion-panel-header>
                    <v-expansion-panel-content class="faq-text">
                        <p id='faq-subtext3'>{{ i.answer }}</p>
                    </v-expansion-panel-content>
                </v-expansion-panel>
            </v-expansion-panels>
        </div>
        <v-divider id="divider"></v-divider>
    </div>
</template>

<script>
export default {
    name: 'FAQView',
    data() {
        return {
            faqitem: [
                {
                    'question': 'Why SCRP coin and not any other coin?',
                    'answer': 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.',
                },
                {
                    'question': 'What is DeSi?',
                    'answer': 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.',
                },
                {
                    'question': 'How is SCRP so stable?',
                    'answer': 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.',
                },
            ],
        }
    }

}
</script>
<style>
#faq-text{
    margin: .25%;
    font-family: 'Staatliches', cursive;
    font-size: 125%;
    color: black;
}
#faq-subtext2{
    margin: .25%;
    font-family: 'Staatliches', cursive;
    color: black;
    font-size: 150%;
    text-align: center;
}
#faq-subtext3{
    margin: .25%;
    font-family: 'Staatliches', cursive;
    color: black;
    font-size: 100%;
    text-align: center;
}
#faq-subtext{
    margin: .25%;
    font-family: 'Staatliches', cursive;
    color: #717171;
}
.text-container{
    margin: 2.5%;
}
.expansion-container{
    width: 65%;
    margin-top: 2.5%;
    margin-bottom: 2.5%;
}
#divider{
    margin-top: 6.5%;
    margin-bottom: 6.5%;
    width: 85%;
    margin-left: auto;
    margin-right: auto;
}
</style>