<template>
  <div>
    <curve/>
    <paramsfield/>
    <mathField/>
    <vectorfield/>
    <surfacefield/>
  </div>
</template>

<script>
import mathField from './field/math'
import curve from './field/curve'
import vectorfield from './field/vector'
import paramsfield from './field/params'
import surfacefield from './field/surface'

export default {
  components:{
  mathField,curve,vectorfield,paramsfield,surfacefield,
  }
}
</script>