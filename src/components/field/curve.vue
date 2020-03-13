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
          detialLink: "grasshoppercurve/polyLine.html"
        },
        {
          name_en: "Explode",
          name_zh: "炸开",
          icon: require("../../assets/curve/Explode.png"),
          discribetion_en: "Explode a curve into smaller segments.",
          discribetion_zh: "将曲线拆分成更小的线段。",
          detialLink: "grasshoppercurve/explode.html"
        },
        {
          name_en: "JoinCurve",
          name_zh: "合并曲线",
          icon: require("../../assets/curve/JoinCurve.png"),
          discribetion_en: "Join as many curves as possible.",
          discribetion_zh: "将曲线拆分成更小的线段。",
          detialLink: "grasshoppercurve/joinCurves.html"
        },
        {
          name_en: "Fillet",
          name_zh: "倒角",
          icon: require("../../assets/curve/Fillet.png"),
          discribetion_en: "Fillet the sharp corners of a curve.",
          discribetion_zh: "对曲线的锐角进行倒角。",
          detialLink: "grasshoppercurve/fillet.html"
        },
        {
          name_en: "Nurbs Curve",
          name_zh: "Nurbs曲线",
          icon: require("../../assets/curve/NurbsCurve.png"),
          discribetion_en: "Construct a nurbs curve from control points.",
          discribetion_zh: "使用控制点构造一条Nurbs曲线。",
          detialLink: "grasshoppercurve/nurbsCurve.html"
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
