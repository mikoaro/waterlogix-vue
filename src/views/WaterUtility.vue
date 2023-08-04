<template>
  <DashBar />
  <side-nav />
  <div class="pa-10 pt-5">
    <h2 class="font-weight-medium mt-10">Water Utility</h2>
    <v-row>
      <v-col cols="12" sm="6">
        <v-card variant="flat" rounded="0" class="bg-grey-darken-3">
          <v-card-title class="text-blue-lighten-2">Tank 1</v-card-title>
          <v-row class="pa-5">
            <v-col cols="12" sm="10">
              <h5 class="font-weight-regular">Tank 1 Level</h5>
            </v-col>
            <v-col cols="12" sm="2">
              <h5 class="font-weight-regular text-end">4</h5>
            </v-col>
            <v-col cols="12" sm="6">
              <utility-chart />
              <h4 class="font-weight-regular mt-5">Low Stpt 135</h4>
            </v-col>
            <v-col cols="12" sm="6">
              <utility-chart />
              <h4 class="font-weight-regular mt-5">High Stpt 215</h4>
            </v-col>
          </v-row>
        </v-card>
      </v-col>
      <v-col cols="12" sm="6">
        <v-card variant="flat" rounded="0" class="bg-grey-darken-3">
          <v-card-title class="text-blue-lighten-2">Tank 2</v-card-title>
          <v-row class="pa-5">
            <v-col cols="12" sm="10">
              <h5 class="font-weight-regular">Tank 2 Level</h5>
            </v-col>
            <v-col cols="12" sm="2">
              <h5 class="font-weight-regular text-end">4</h5>
            </v-col>
            <v-col cols="12" sm="6">
              <utility-chart />
              <h4 class="font-weight-regular mt-5">Low Stpt 135</h4>
            </v-col>
            <v-col cols="12" sm="6">
              <utility-chart />
              <h4 class="font-weight-regular mt-5">High Stpt 215</h4>
            </v-col>
          </v-row>
        </v-card>
      </v-col>
      <!-- water well -->
      <v-col cols="12" sm="4">
        <v-card variant="flat" rounded="0" class="bg-grey-darken-3">
          <v-card-title class="text-blue-lighten-2">Water Well</v-card-title>
          <v-row class="pa-5" no-gutters="">
            <v-col cols="12" sm="2">
              <h5 class="font-weight-regular">Mode:</h5>
            </v-col>
            <v-col cols="12" sm="3">
              <h5 class="font-weight-bold">Manual</h5>
            </v-col>
            <v-col cols="12" sm="2">
              <h5 class="font-weight-regular">Status:</h5>
            </v-col>
            <v-col cols="12" sm="3">
              <h5 class="font-weight-bold">Stopped</h5>
            </v-col>
          </v-row>
          <v-row class="pa-5" no-gutters="">
            <v-col cols="12" sm="2">
              <h5 class="font-weight-regular mt-4">Mode</h5>
            </v-col>
            <v-col cols="12" sm="3">
              <v-switch></v-switch>
            </v-col>
            <v-col cols="12" sm="2">
              <h5 class="font-weight-regular mt-4">run</h5>
            </v-col>
            <v-col cols="12" sm="3">
              <v-switch></v-switch>
            </v-col>
          </v-row>
        </v-card>
      </v-col>

      <!-- Transfer Pump -->
      <v-col cols="12" sm="4">
        <v-card variant="flat" rounded="0" class="bg-grey-darken-3">
          <v-card-title class="text-blue-lighten-2">Transfer Pump</v-card-title>
          <v-row class="pa-5" no-gutters="">
            <v-col cols="12" sm="2">
              <h5 class="font-weight-regular">Mode:</h5>
            </v-col>
            <v-col cols="12" sm="3">
              <h5 class="font-weight-bold">Manual</h5>
            </v-col>
            <v-col cols="12" sm="2">
              <h5 class="font-weight-regular">Status:</h5>
            </v-col>
            <v-col cols="12" sm="3">
              <h5 class="font-weight-bold">Stopped</h5>
            </v-col>
          </v-row>
          <v-row class="pa-5" no-gutters="">
            <v-col cols="12" sm="2">
              <h5 class="font-weight-regular mt-4">Mode</h5>
            </v-col>
            <v-col cols="12" sm="3">
              <v-switch></v-switch>
            </v-col>
            <v-col cols="12" sm="2">
              <h5 class="font-weight-regular mt-4">run</h5>
            </v-col>
            <v-col cols="12" sm="3">
              <v-switch></v-switch>
            </v-col>
          </v-row>
        </v-card>
      </v-col>

      <!-- Alarming -->
      <v-col cols="12" sm="4">
        <v-card variant="flat" rounded="0" class="bg-grey-darken-3">
          <v-card-title class="text-blue-lighten-2">Alarming</v-card-title>
          <v-row class="pa-5" no-gutters="">
            <v-col cols="12" sm="5">
              <h5 class="font-weight-regular mt-4">Enable Audio TTS</h5>
            </v-col>
            <v-spacer></v-spacer>
            <v-col cols="12" sm="3">
              <v-switch></v-switch>
            </v-col>
          </v-row>
        </v-card>
      </v-col>
    </v-row>
  </div>
</template>

<script setup>
import DashBar from "@/components/dashboard//DashBar.vue";
import SideNav from "@/components/dashboard/SideNav.vue";
import UtilityChart from "@/components/dashboard/UtilityChart.vue";
</script>

<style></style>
