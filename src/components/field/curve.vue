<template>
  <div>
    <contentfield :maincontent="content" title="Curve" />
  </div>
</template>
<script>
import contentfield from "../field";
export default {
  components: {
    contentfield
  },
  data() {
    return {
      content: [
        {
          name_en: "PolyLine",
          name_zh: "折线",
          icon: require("../../assets/curve/PolyLine.png"),
          discribetion_en: "Create a polyline connecting a number of points.",
          discribetion_zh: "生成一条连接若干点的折线。",
          detialLink:
            "http://grasshopperdocs.com/components/grasshoppercurve/polyLine.html"
        },
        {
          name_en: "Explode",
          name_zh: "炸开",
          icon: require("../../assets/curve/Explode.png"),
          discribetion_en: "Explode a curve into smaller segments.",
          discribetion_zh: "将曲线拆分成更小的线段。",
          detialLink:
            "http://grasshopperdocs.com/components/grasshoppercurve/explode.html"
        },
        {
          name_en: "JoinCurve",
          name_zh: "合并曲线",
          icon: require("../../assets/curve/JoinCurve.png"),
          discribetion_en: "Join as many curves as possible.",
          discribetion_zh: "将曲线拆分成更小的线段。",
          detialLink:
            "http://grasshopperdocs.com/components/grasshoppercurve/joinCurves.html"
        }
      ]
    };
  }
};
</script>
<style>
hr.styleone {
  border: 0;
  height: 0.8px;
  background: rgb(105, 105, 105);
  background-image: linear-gradient(to right, #ccc, rgb(105, 105, 105), #ccc);
}
</style>
