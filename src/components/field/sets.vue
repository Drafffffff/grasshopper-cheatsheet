<template>
  <div>
    <contentfield :maincontent="content" title="Sets" />
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
          name_en: "Range",
          name_zh: "范围",
          icon: require("../../assets/set/Range.png"),
          discribetion_en: "Create a range of numbers.",
          discribetion_zh: "创建一系列数字。",
          detialLink: "grasshoppersets/range.html"
        },
        {
          name_en: "Series",
          name_zh: "数列",
          icon: require("../../assets/set/Series.png"),
          discribetion_en: "Create a series of numbers.",
          discribetion_zh: "创建一系列数字。",
          detialLink: "grasshoppersets/series.html"
        },
        {
          name_en: "ListItem",
          name_zh: "列表项",
          icon: require("../../assets/set/listItem.png"),
          discribetion_en: "Retrieve a specific item from a list.",
          discribetion_zh: "从列表中检索特定项。",
          detialLink: "grasshoppersets/listItem.html"
        },
        {
          name_en: "CullIndex",
          name_zh: "删除索引",
          icon: require("../../assets/set/CullIndex.png"),
          discribetion_en: "Solve the arithmetic average for a set of items.",
          discribetion_zh: "从列表中删除（删除）索引元素。",
          detialLink: "grasshoppersets/cullIndex.html"
        },
        {
          name_en: "ListLength",
          name_zh: "列表长度",
          icon: require("../../assets/set/ListLength.png"),
          discribetion_en: "Measure the length of a list.",
          discribetion_zh: "获取列表长度。",
          detialLink: "grasshoppersets/listLength.html"
        },
        {
          name_en: "Random",
          name_zh: "随机数",
          icon: require("../../assets/set/Random.png"),
          discribetion_en: "Generate a list of pseudo random numbers.",
          discribetion_zh: "生成伪随机数列表。",
          detialLink: "grasshoppersets/random.html"
        }
      ]
    };
  }
};
</script>
