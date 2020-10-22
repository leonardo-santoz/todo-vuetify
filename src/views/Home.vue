<template>
<div class="home pl-10 pr-10">
    <h1>Homepage</h1>
    <div class="d-flex justify-space-between">
        <v-btn class="purple white--text">Click me</v-btn>
        <v-btn depress dark color="purple">Click me</v-btn>
        <v-btn flat>Click me</v-btn>

        <v-btn depressed class="pink white--text">
            <v-icon> mdi-account gram </v-icon>
            <span>Conta</span>
        </v-btn>

        <v-btn depressed small class="pink white--text">
            <v-icon> mdi-account gram </v-icon>
            <span>Conta</span>
        </v-btn>

        <v-btn depressed large class="pink white--text">
            <span>Conta</span>
            <v-icon> mdi-account gram </v-icon>
        </v-btn>

        <v-btn depressed fab small dark class="pink white--text">
            <v-icon>mdi-bell-ring</v-icon>
        </v-btn>

        <v-btn depressed fab medium dark class="pink white--text">
            <v-icon>mdi-bell-ring</v-icon>
        </v-btn>

        <v-btn depressed fab medium dark class="blue white--text">
            <v-icon large>mdi-plus</v-icon>
        </v-btn>
    </div>
</div>
</template>

<script>
export default {};
</script>
