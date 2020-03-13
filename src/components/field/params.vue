<template>
  <div>


  <contentfield :maincontent="content" title="Params"/>
    
  </div>
</template>
<script>
import contentfield from '../field'
export default {
  // name:"mathfield",
  components:{
    contentfield
  },
  data() {
    return {
      content: [
        {
          name_en: "Addition",
          name_zh: "加",
          icon:
            "https://drafff.oss-cn-beijing.aliyuncs.com/img/20200313000931.png",
          discribetion_en: "Mathematical addition",
          discribetion_zh: "数学加法",
          input: [
            { name: "A", id: "A", description: "加法的第一项" },
            { name: "B", id: "B", description: "加法的第二项" }
          ],
          output: [{ name: "Result", id: "R", description: "运算结果" }],
          detialLink:
            "http://grasshopperdocs.com/components/grasshoppermaths/addition.html"
        },
        {
          name_en: "Addition",
          name_zh: "加",
          icon:
            "https://drafff.oss-cn-beijing.aliyuncs.com/img/20200313000931.png",
          discribetion_en: "Mathematical addition",
          discribetion_zh: "数学加法",
          input: [
            { name: "A", id: "A", description: "加法的第一项" },
            { name: "B", id: "B", description: "加法的第二项" }
          ],
          output: [{ name: "Result", id: "R", description: "运算结果" }],
          detialLink:
            "http://grasshopperdocs.com/components/grasshoppermaths/addition.html"
        },
        {
          name_en: "Addition",
          name_zh: "加",
          icon:
            "https://drafff.oss-cn-beijing.aliyuncs.com/img/20200313000931.png",
          discribetion_en: "Mathematical addition",
          discribetion_zh: "数学加法",
          input: [
            { name: "A", id: "A", description: "加法的第一项" },
            { name: "B", id: "B", description: "加法的第二项" }
          ],
          output: [{ name: "Result", id: "R", description: "运算结果" }],
          detialLink:
            "http://grasshopperdocs.com/components/grasshoppermaths/addition.html"
        },
        {
          name_en: "Addition",
          name_zh: "加",
          icon:
            "https://drafff.oss-cn-beijing.aliyuncs.com/img/20200313000931.png",
          discribetion_en: "Mathematical addition",
          discribetion_zh: "数学加法",
          input: [
            { name: "A", id: "A", description: "加法的第一项" },
            { name: "B", id: "B", description: "加法的第二项" }
          ],
          output: [{ name: "Result", id: "R", description: "运算结果" }],
          detialLink:
            "http://grasshopperdocs.com/components/grasshoppermaths/addition.html"
        },
        {
          name_en: "Addition",
          name_zh: "加",
          icon:
            "https://drafff.oss-cn-beijing.aliyuncs.com/img/20200313000931.png",
          discribetion_en: "Mathematical addition",
          discribetion_zh: "数学加法",
          input: [
            { name: "A", id: "A", description: "加法的第一项" },
            { name: "B", id: "B", description: "加法的第二项" }
          ],
          output: [{ name: "Result", id: "R", description: "运算结果" }],
          detialLink:
            "http://grasshopperdocs.com/components/grasshoppermaths/addition.html"
        }
      ]
    };
  }
};
</script>
<style>
hr.styleone{
 
    border: 0;
    height: 0.8px;
    background: rgb(105, 105, 105);
    background-image: linear-gradient(to right, #ccc, rgb(105, 105, 105), #ccc);

}
</style>
