<template>
  <div>
    <curve/>
    <mathField/>
    <setsfield/>
    <transformfield/>
    <surfacefield/>
    <vectorfield/>
    <paramsfield/>
  </div>
</template>

<script>
import mathField from './field/math'
import curve from './field/curve'
import vectorfield from './field/vector'
import paramsfield from './field/params'
import surfacefield from './field/surface'
import setsfield from './field/sets'
import transformfield from './field/transform'

export default {
  components:{
  mathField,curve,vectorfield,paramsfield,surfacefield,setsfield,transformfield,
  }
}
</script>