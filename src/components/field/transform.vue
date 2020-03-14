<template>
  <div>
    <contentfield :maincontent="content" title="Transform" />
  </div>
</template>
<script>
import contentfield from "../field";
export default {
  // name:"mathfield",
  components: {
    contentfield
  },
  data() {
    return {
      content: [
        {
          name_en: "Move",
          name_zh: "移动",
          icon: require("../../assets/transform/Move.png"),
          discribetion_en: "Translate (move) an object along a vector.",
          discribetion_zh: "沿矢量平移（移动）对象。",
          detialLink: "grasshoppertransform/move.html"
        },
        {
          name_en: "Scale",
          name_zh: "缩放",
          icon: require("../../assets/transform/Scale.png"),
          discribetion_en: "Scale an object uniformly in all directions.",
          discribetion_zh: "在所有方向统一缩放对象。",
          detialLink: "grasshoppertransform/scale.html"
        },
        {
          name_en: "ScaleNU",
          name_zh: "缩放NU",
          icon: require("../../assets/transform/ScaleNU.png"),
          discribetion_en: "Scale an object with non-uniform factors.",
          discribetion_zh: "使用不均匀因子缩放对象。",
          detialLink: "grasshoppertransform/scaleNU.html"
        },
        {
          name_en: "Rotate",
          name_zh: "旋转",
          icon: require("../../assets/transform/Rotate.png"),
          discribetion_en: "Rotate an object in a plane.",
          discribetion_zh: "在平面中旋转对象。",
          detialLink: "grasshoppertransform/rotate.html"
        },
        {
          name_en: "SurfaceBox",
          name_zh: "表面框",
          icon: require("../../assets/transform/SurfaceBox.png"),
          discribetion_en: "Create a twisted box on a surface patch.",
          discribetion_zh: "在曲面贴片上创建扭曲框。",
          detialLink: "grasshoppertransform/surfaceBox.html"
        },
        {
          name_en: "BoxMorph",
          name_zh: "框变形",
          icon: require("../../assets/transform/BoxMorph.png"),
          discribetion_en: "Morph an object into a twisted box.",
          discribetion_zh: "将对象变形为扭曲的盒子。",
          detialLink: "grasshoppertransform/boxMorph.html"
        }
      ]
    };
  }
};
</script>
