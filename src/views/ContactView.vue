<template>
    <div align="center" justify="center">
        <div class="text-container">
            <h1>Contact Us</h1>
            <p id='title-subtext'>How can we help you?</p>
        </div>
        <v-divider id="divider"></v-divider>
        <v-col class="card-container" align="center" justify="center">
            <v-card shaped class="contact-form-card" max-width="374">
                <v-form v-model="valid">
                    <v-container>
                        <v-col>
                            <v-text-field v-model="firstname" :counter="10" label="Name" required></v-text-field>
                        </v-col>
                        <v-col>
                            <v-text-field v-model="email" label="E-mail" required></v-text-field>
                        </v-col>
                        <v-col>
                            <v-textarea clearable clear-icon="mdi-close-circle" label="Your question"></v-textarea>
                        </v-col>
                    </v-container>
                        <v-col>
                            <v-btn color="black" block><h3 id="btn-text">Submit</h3></v-btn>
                        </v-col>
                </v-form>
            </v-card>
        </v-col>
        <v-divider id="divider"></v-divider>
    </div>
</template>

<script>
export default {

}
</script>

<style>
.card-container{
    margin: auto;
}
#btn-text{
    color: white;
}
.contact-form-card{
    width: 70%;
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
</style>