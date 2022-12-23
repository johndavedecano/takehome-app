<template>
    <v-layout full-height>
        <v-row justify="center" align-content="center">
            <v-col md="5" lg="4" xl="3">
                <v-container fluid>
                    <v-card class="elevation-12">
                        <v-card-item class="px-8 py-8">
                            <v-card-title class="font-weight-bold text-h5 mb-1">Sign in</v-card-title>
                            <v-card-subtitle>Welcome back! Login to get started</v-card-subtitle>
                        </v-card-item>
                        <v-card-text class="px-8 pb-10">
                            <v-form>
                                <v-text-field name="email" label="Email" type="email"></v-text-field>
                                <v-text-field id="password" name="password" label="Password"
                                    type="password"></v-text-field>
                                <v-btn block type="submit" class="mb-2" variant="flat" size="large" color="primary">Login</v-btn>
                                <v-btn block class="mb-4" variant="link" color="primary" to="/forgot">Forgot password?</v-btn>
                                <v-btn block class="mb-4" variant="outlined"  size="large" color="primary" to="/register">I dont have an account yet</v-btn>
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