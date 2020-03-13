<template>
  <div>

    <div class="container mx-auto mt-10 sm:max-w-xl md:max-w-3xl lg:max-w-4xl ">
      <p
        class="text-4xl font-light tracking-wider text-gray-800 text-center sm:text-left"
      >
        <a
          class=" hover:bg-indigo-500 hover:text-white font-light text-gray-700 "
          href="#"
        >
          #</a
        >{{title}}
        <hr class="styleone">
        
      </p>


      <div class=" flex flex-wrap flex-col sm:flex-row   py-6">
        <div
          class="sm:w-1/2 lg:w-1/3 px-5  pb-12"
          v-for="(item, index) in maincontent"
          :key="index"
        >
          <div class="text-lg font-bold text-indigo-700 mb-1">
            <div class="flex">
              <img
                class="inline justify-center object-cover w-6 h-6 "
                :src="item.icon"
                :alt="item.name_en"
              />
              <span class="ml-2">
                {{ item.name_en + " - " + item.name_zh }}
              </span>
            </div>
          </div>
          <div
            class="bg-white mt-2 rounded-md shadow-lg hover:shadow-2xl  transition ease duration-200 hover:scale-105 transform "
          >
            <div class=" text-sm px-4 pt-10 pb-5 text-gray-700">
              <p>{{ item.discribetion_en }}</p>
              <p>{{ item.discribetion_zh }}</p>
            </div>
            <p class="text-xs text-right p-2 pr-4 text-gray-600">
              <a :href="'http://grasshopperdocs.com/components/'+ item.detialLink">了解更多></a>
            </p>
          </div>
        </div>
      </div>
    </div>

  </div>
</template>


<script>
export default {
  // name: "field",
  props:["maincontent","title"]
}
</script>

<style>
hr.styleone {
  border: 0;
  height: 0.8px;
  background: rgb(105, 105, 105);
  background-image: linear-gradient(to right, #ccc, rgb(105, 105, 105), #ccc);
}
</style>