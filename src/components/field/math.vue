<template>
  <div>


  <contentfield :maincontent="content" title="Maths"/>
    
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
          icon:require("../../assets/math/Addition.png"),
          discribetion_en: "Mathematical addition",
          discribetion_zh: "数学加法",
          detialLink:
            "grasshoppermaths/addition.html"
        },
      ]
    };
  }
};
</script>
