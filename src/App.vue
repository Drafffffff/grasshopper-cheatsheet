<template>
  <div id="app" class="bg-gray-100">
    <maintitle></maintitle>
    <fields />
    <pagefooter />
  </div>



</template>

<script>
import maintitle from "./components/title.vue";
import fields from "./components/fields";
import pagefooter from "./components/pagefooter";
export default {
  name: "App",
  components: {
    maintitle,
    fields,
    pagefooter
  }
};
</script>

<style lang="stylus">
body{
	margin: 0; 
	padding: 0;
	border: 0;
}
</style>


