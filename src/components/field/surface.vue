<template>
  <div>
    <contentfield :maincontent="content" title="Surface" />
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
          name_en: "Extrude",
          name_zh: "挤出",
          icon: require("../../assets/surface/Extrude.png"),
          discribetion_en: "Extrude curves and surfaces along a vector.",
          discribetion_zh: "沿矢量拉伸曲线和曲面。",
          detialLink: "grasshoppersurface/extrude.html"
        },
        {
          name_en: "Loft",
          name_zh: "挤出",
          icon: require("../../assets/surface/Loft.png"),
          discribetion_en: "Create a lofted surface through a set of section curves.",
          discribetion_zh: "通过一组剖面曲线创建放样曲面。",
          detialLink: "grasshoppersurface/loft.html"
        },
        {
          name_en: "OffsetSurface",
          name_zh: "偏移曲面",
          icon: require("../../assets/surface/OffsetSurface.png"),
          discribetion_en: "Offset a surface by a fixed amount.",
          discribetion_zh: "将曲面偏移固定量。",
          detialLink: "grasshoppersurface/offsetSurface.html"
        },
        {
          name_en: "BoundarySurfaces",
          name_zh: "创建边界曲面",
          icon: require("../../assets/surface/BoundarySurfaces.png"),
          discribetion_en: "Create planar surfaces from a collection of boundary edge curves.",
          discribetion_zh: "从边界边曲线集合创建平面曲面。",
          detialLink: "grasshoppersurface/boundarySurfaces.html"
        },
        {
          name_en: "CapHoles",
          name_zh: "加盖",
          icon: require("../../assets/surface/CapHoles.png"),
          discribetion_en: "Cap all planar holes in a Brep.",
          discribetion_zh: "给所有的平面洞加盖。",
          detialLink: "grasshoppersurface/capHoles.html"
        },
        {
          name_en: "BoundingBox",
          name_zh: "边界框",
          icon: require("../../assets/surface/BoundingBox.png"),
          discribetion_en: "Solve oriented geometry bounding boxes.",
          discribetion_zh: "求出几何体的边界框。",
          detialLink: "grasshoppersurface/boundingBox.html"
        }
        
      ]
    };
  }
};
</script>
