<template>
  <v-table>
    <thead>
      <tr>
        <th class="text-left"></th>
        <th class="text-left bg-grey-lighten-3">Order Total</th>
      </tr>
    </thead>
    <tbody>
      <tr v-for="item in desserts" :key="item.name">
        <td class="bg-grey-lighten-3">{{ item.name }}</td>
        <td class="text-right">{{ item.totalOrder }}</td>
      </tr>
    </tbody>
  </v-table>
</template>
<script>
export default {
  data() {
    return {
      desserts: [
        {
          name: "F-camera",
          totalOrder: "159k",
        },
        {
          name: "G-washer",
          totalOrder: "237k",
        },
        {
          name: "B-receiver",
          totalOrder: "262k",
        },
        {
          name: "A-receiver",
          totalOrder: "305k",
        },
        {
          name: "A-phone",
          totalOrder: "305k",
        },
        {
          name: "B-phone",
          totalOrder: "305k",
        },
        {
          name: "A-head",
          totalOrder: "305k",
        },
        {
          name: "A-head",
          totalOrder: "305k",
        },
        {
          name: "A-head",
          totalOrder: "305k",
        },
        
      ],
    };
  },
};
</script>
