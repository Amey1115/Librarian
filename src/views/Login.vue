<template>
    <div class="center">
        <v-row>
            <v-col cols="10" sm="6" offset-sm="3" md="4" offset-md="4" offset="1">
                <v-avatar size="100" tile>
                    <v-img src="@/assets/thelogo.png"></v-img>
                </v-avatar>

                <v-text-field label="Username" v-model="username"></v-text-field>
                <v-text-field label="Password" v-model="password" type="password"></v-text-field>
                <v-btn type="submit" @click="auth()">
                    Login
                </v-btn>

            </v-col>
        </v-row>
    </div>
</template>

<script>
export default {
    data() {
        username = "";
        password = "";
    },
    methods: {
        auth() {
            if (this.username == "ameybayas@gmail.com" && this.password == "pwd") {
                alert("Welcome Amey")
            }
            else {
                alert("Wrong Password")
            }
        }
    },

}
</script>

<style lang="scss" scoped></style>