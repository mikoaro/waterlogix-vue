<template>
  <Chart style="height:150px">
    <chartArea background-color="rgb(16, 43, 213)">
      <ChartSeries>
      <ChartSeriesItem :color="'rgb(16, 43, 213)'" :type="'column'" :data-items="firstSeries" />
    </ChartSeries>
    </chartArea>
  </Chart>
</template>
<script>
import {
  Chart,
  ChartSeries,
  ChartSeriesItem,
  ChartArea,
} from "@progress/kendo-vue-charts";
import "hammerjs";
import "@progress/kendo-theme-default/dist/all.css";

export default {
  components: {
    Chart,
    ChartSeries,
    ChartSeriesItem,
    ChartArea
  },
  data: function () {
    return {
      firstSeries: [4],
    };
  },
};
</script>
<style>
.a{
  color: rgb(40, 39, 39);
}
</style>
