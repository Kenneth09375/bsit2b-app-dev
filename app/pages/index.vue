<template>
  <div>
    <h1>Welcome to My Nuxt App</h1>
    <v-btn>Submit</v-btn>

    <v-row>
      <v-col cols="12" md="3">
        <v-card height="150" color="blue">
          <v-card-text>
            <v-row>
              <v-col cols="6">
                <v-icon size="100"> mdi-account-circle</v-icon>
              </v-col>
              <v-col cols="6">
                <v-row no-gutters>
                  <v-col cols="12" class="text-h6 text-right"> STUDENT </v-col>
                  <v-col cols="12" class="text-h6 text-right font-weight-bold">
                    250
                  </v-col>
                </v-row>
                <v-icon></v-icon>
              </v-col>
            </v-row>
          </v-card-text>
        </v-card>
      </v-col>

      <v-col cols="12" md="3">
        <v-card height="150" color="red"></v-card>
      </v-col>

      <v-col cols="12" md="3">
        <v-card height="150" color="yellow"></v-card>
      </v-col>

      <v-col cols="12" md="3">
        <v-card height="150" color="orange"></v-card>
      </v-col>
    </v-row>
  </div>
</template>

<script lang="ts" setup>
</script>

<style></style>