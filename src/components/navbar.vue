<template>
    <v-app-bar app color="white">
        <a href="/" class="d-flex align-center">
            <v-img
            alt="Logo"
            href="https://google.com"
            class="shrink mr-2"
            contain
            src="../assets/images/logo2.png"
            transition="scale-transition"
            max-width="100"
            />
        </a>
        <div v-if="isMobile" class="buttonContainer">
            <v-btn href="/about" class="navButton" text>How it works</v-btn>
            <v-btn href="/innovation" class="navButton" text>Innovation</v-btn>
            <v-btn href="/participate" class="navButton" text>Participate</v-btn>
            <v-btn href="/community" class="navButton" text>Community<v-icon size="15" color="red">mdi-alert-octagram</v-icon></v-btn>
            <v-btn href="/faq" class="navButton" text>FAQ</v-btn>
        </div>
        <v-spacer v-if="!isMobile"></v-spacer>
        <div v-if="!isMobile" id="mobileMenuBtn" class="text-center">
            <v-menu offset-y>
                <template v-slot:activator="{ on, attrs }">
                    <v-btn color="primary" text v-bind="attrs" v-on="on">
                        <v-icon color="black">mdi-menu</v-icon>
                    </v-btn>
                </template>
                <v-list>
                    <v-list-item v-for="(item, index) in menuitems" :key="index">
                        <v-btn :href="item.link" class="navButton" text>{{ item.title }}</v-btn>
                    </v-list-item>
                </v-list>
            </v-menu>
        </div>
        </v-app-bar>
</template>
<script>
export default {
    name: 'Navbar',
    data: () => ({
        isMobile: false,
        menuitems: [
            { title: 'How it works', link: '/about' },
            { title: 'Innovation', link: '/innovation'},
            { title: 'Participate', link: '/participate' },
            { title: 'Community', link: '/community' },
            { title: 'FAQ', link: '/faq' },
        ],
    }),
    mounted() {
        if(window.innerWidth > 760){
            this.isMobile = true;
        }
        else{
            this.isMobile = false;
        }
    },
    methods: {
        getWindowSize(){
            console.log(window.innerWidth)
        },
    },

}
</script>
<style>
v-app-bar {
    position: fixed;
}
#mobileMenuBtn{
    padding: 10px;
}
.buttonContainer{
    padding: 10px;
    margin: auto;
}
.navButton{
    font-family: Bank Sans EF CY, serif;
}
</style>