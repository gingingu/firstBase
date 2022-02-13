<template>
  <div>
      <h2>我爱你喻晋</h2>
      <button @click="count++">爱了{{count}}</button>
  </div>
</template>

<script>
export default {
    name:'',
    data(){
        return {
            count:0
        }
    }
}
</script>

<style>
    h2{
        color: deeppink
    }
</style>