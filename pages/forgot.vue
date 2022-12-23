<template>
    <v-layout full-height>
        <v-row justify="center" align-content="center">
            <v-col md="5" lg="4" xl="3">
                <v-container fluid>
                    <v-card class="elevation-12">
                        <v-card-item class="px-8 py-8">
                            <v-card-title class="font-weight-bold text-h5 mb-1">Forgot Password</v-card-title>
                            <v-card-subtitle>
                                We are happy to help you with your password.
                            </v-card-subtitle>
                        </v-card-item>
                        <v-card-text class="px-8 pb-10">
                            <v-form>
                                <v-text-field name="email" label="Email" type="email"></v-text-field>
                                <v-btn block type="submit" class="mb-1" size="large" variant="flat" color="primary">Verify Account</v-btn>
                                <v-btn block variant="link" color="primary" to="/login">I can still remember my password</v-btn>
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