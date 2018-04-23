<template>
  <div style="height:100%">
  <my-header></my-header>
  <p>我的主题内容部分</p>
  </div>
</template>
<script>
import myHeader from '../components/myHeader.vue'
export default {
  head: {
    title: '简书-创作你的创作',
    meta: [
      { charset: "utf-8" },
      { name: "keywords", content: "简书首页" },
      { name: "dscription", content: "简书首页" },
      { name: "author", content: "赵超" }
    ]
  },
    components:{
            myHeader
        },
  data() {
    return {
      name: "首页"
    };
  }
};
</script>
<style>

</style>

