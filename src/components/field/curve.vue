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
          name_en: "NurbsCurve",
          name_zh: "Nurbs曲线",
          icon: require("../../assets/curve/NurbsCurve.png"),
          discribetion_en: "Construct a nurbs curve from control points.",
          discribetion_zh: "使用控制点构造一条Nurbs曲线。",
          detialLink: "grasshoppercurve/nurbsCurve.html"
        },
        {
          name_en: "InterPolate",
          name_zh: "插值曲线",
          icon: require("../../assets/curve/InterPolate.png"),
          discribetion_en:
            "Create an interpolated curve through a set of points.",
          discribetion_zh: "通过一组点创建插值曲线。",
          detialLink: "grasshoppercurve/interpolate.html"
        },
        {
          name_en: "ControlPoint",
          name_zh: "提取控制点",
          icon: require("../../assets/curve/ControlPoint.png"),
          discribetion_en:
            "Extract the nurbs control points and knots of a curve.",
          discribetion_zh: "提取曲线的 nurbs 控制点和结（knots）",
          detialLink: "grasshoppercurve/controlPoints.html"
        },
        {
          name_en: "ControlPolygon",
          name_zh: "提取控制多边形",
          icon: require("../../assets/curve/ControlPolygon.png"),
          discribetion_en: "Extract the nurbs control polygon of a curve.",
          discribetion_zh: "提取曲线的nurbs控制多边形。",
          detialLink: "grasshoppercurve/controlPolygon.html"
        },
        {
          name_en: "DivideCurve",
          name_zh: "分割曲线",
          icon: require("../../assets/curve/DivideCurve.png"),
          discribetion_en: "Divide a curve into equal length segments.",
          discribetion_zh: "将曲线划分为相等长度的线段。",
          detialLink: "grasshoppercurve/divideCurve.html"
        },
        {
          name_en: "DivideLength",
          name_zh: "分割曲线",
          icon: require("../../assets/curve/DivideLength.png"),
          discribetion_en: "Divide a curve into segments with a preset length.",
          discribetion_zh: "将曲线按照预设长度划分为等长的线段",
          detialLink: "grasshoppercurve/divideLength.html"
        },
        {
          name_en: "DivideDistance",
          name_zh: "分割曲线",
          icon: require("../../assets/curve/DivideDistance.png"),
          discribetion_en: "Divide a curve with a preset distance between points.",
          discribetion_zh: "将曲线按照预设距离划分为等长的线段",
          detialLink: "grasshoppercurve/divideDistance.html"
        }
      ]
    };
  }
};
</script>

