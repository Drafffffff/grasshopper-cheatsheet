<template>
  <div>
    <contentfield :maincontent="content" title="Vectors" />
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
          name_en: "UnitX",
          name_zh: "单位矢量X",
          icon: require("../../assets/vector/UnitX.png"),
          discribetion_en: "Unit vector parallel to the world {x} axis.",
          discribetion_zh: "与世界 [x] 轴平行的单位矢量。",
          detialLink: "grasshoppervector/unitX.html"
        },
        {
          name_en: "UnitY",
          name_zh: "单位矢量Y",
          icon: require("../../assets/vector/UnitY.png"),
          discribetion_en: "Unit vector parallel to the world {y} axis.",
          discribetion_zh: "与世界 [y] 轴平行的单位矢量。",
          detialLink: "grasshoppervector/unitY.html"
        },
        {
          name_en: "UnitZ",
          name_zh: "单位矢量Z",
          icon: require("../../assets/vector/UnitZ.png"),
          discribetion_en: "Unit vector parallel to the world {z} axis.",
          discribetion_zh: "与世界 [z] 轴平行的单位矢量。",
          detialLink: "grasshoppervector/unitZ.html"
        }
      ]
    };
  }
};
</script>
