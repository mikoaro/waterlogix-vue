<template>
  <v-navigation-drawer class="bg-grey-darken-3" theme="dark" floating permanent width="200">
    <v-list>
      <v-list-item link to="/dashboard" prepend-icon="mdi-view-dashboard" title="Dashboard">
      </v-list-item>
    </v-list>

    <!-- bottom -->
    <!-- <template v-slot:append>
      <v-list>
        <v-list-item
        link
          prepend-icon="mdi-plus-circle-outline"
          title="New"
        ></v-list-item>
        <v-list-item
        link
          prepend-icon="mdi-tray-arrow-up"
          title="Upload files"
        ></v-list-item>
        <v-list-item
        link
          prepend-icon="mdi-message-outline"
          title="Notifications"
        ></v-list-item>
        <v-list-item
        link
          prepend-icon="mdi-check-circle-outline"
          title="Manage"
        ></v-list-item>
      </v-list>
    </template> -->
  </v-navigation-drawer>
</template>

<script setup></script>

<style></style>
