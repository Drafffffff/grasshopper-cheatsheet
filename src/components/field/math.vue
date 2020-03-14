<template>
  <div>
    <contentfield :maincontent="content" title="Maths" />
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
          name_en: "ConstructDomain",
          name_zh: "构造值域",
          icon: require("../../assets/math/ConstructDomain.png"),
          discribetion_en: "Create a numeric domain from two numeric extremes.",
          discribetion_zh: "通过最大最小值创建一个值域。",
          detialLink: "grasshoppermaths/constructDomain.html"
        },
        {
          name_en: "Bounds",
          name_zh: "边界",
          icon: require("../../assets/math/Bounds.png"),
          discribetion_en:
            "Create a numeric domain which encompasses a list of numbers.",
          discribetion_zh: "创建一个数字列表的值域。",
          detialLink: "grasshoppermaths/bounds.html"
        },
        {
          name_en: "RemapNumbers",
          name_zh: "重映射",
          icon: require("../../assets/math/RemapNumbers.png"),
          discribetion_en:
            "Remap numbers into a new numeric domain",
          discribetion_zh: "将数字重新映射到新的值域。",
          detialLink: "grasshoppermaths/remapNumbers.html"
        },
        {
          name_en: "Average",
          name_zh: "平均值",
          icon: require("../../assets/math/Average.png"),
          discribetion_en:
            "Solve the arithmetic average for a set of items.",
          discribetion_zh: "求解一组项的算术平均值。",
          detialLink: "grasshoppermaths/average.html"
        },
        {
          name_en: "DivideDomain",
          name_zh: "划分区域",
          icon: require("../../assets/math/DivideDomain.png"),
          discribetion_en:
            "Divide a domain into equal segments.",
          discribetion_zh: "将域划分为相等的段。",
          detialLink: "grasshoppermaths/divideDomain.html"
        }
      ]
    };
  }
};
</script>
