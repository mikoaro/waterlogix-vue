<template>
  <Chart>
    <ChartSeries>
      <ChartSeriesItem
        :color="'rgb(16, 43, 213)'"
        :type="'column'"
        :data-items="firstSeries"
      />
    </ChartSeries>
  </Chart>
</template>
<script>
import {
  Chart,
  ChartSeries,
  ChartSeriesItem,
} from "@progress/kendo-vue-charts";
import "hammerjs";
import "@progress/kendo-theme-default/dist/all.css";

export default {
  components: {
    Chart,
    ChartSeries,
    ChartSeriesItem,
  },
  data: function () {
    return {
      firstSeries: [1, 2, 3, 4, 5, 8, 3, 5],
    };
  },
};
</script>
<style>
.a{
  color: rgb(16, 43, 213);
}
</style>
