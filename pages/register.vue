<template>
    <v-layout full-height>
        <v-row justify="center" align-content="center">
            <v-col md="5" lg="4" xl="3">
                <v-container fluid>
                    <v-card class="elevation-12">
                        <v-card-item class="px-8 py-8">
                            <v-card-title class="font-weight-bold text-h5 mb-1">Sign up Today!</v-card-title>
                            <v-card-subtitle>You will never go wrong. We are happy to get you started.</v-card-subtitle>
                        </v-card-item>
                        <v-card-text class="px-8 pb-10">
                            <v-form>
                                <v-text-field name="name" label="Name" type="text"></v-text-field>

                                <v-text-field name="email" label="Email" type="email"></v-text-field>

                                <v-text-field id="password" name="password" label="Password"
                                    type="password"></v-text-field>


                                <v-text-field id="password_confirmation" name="password_confirmation"
                                    label="Password Confirmation" type="password"></v-text-field>

                                <v-btn block type="submit" size="large" class="mb-4" variant="flat" color="primary">Create an account</v-btn>
                                <v-btn block class="mb-4" variant="link" color="primary" to="/login">I already have
                                    an account</v-btn>
                            </v-form>
                        </v-card-text>
                    </v-card>
                </v-container>
            </v-col>
        </v-row>
    </v-layout>
</template>

<script>
// This will work in both `<script setup>` and `<script>`
definePageMeta({
    layout: "custom",
});
</script>