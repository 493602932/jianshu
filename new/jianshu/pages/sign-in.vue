<template>
  <div class="sign">
    <!-- logo -->
      <div class="logo">
        <nuxt-link to="/">
           <img src="~/assets/img/logo.png">
        </nuxt-link>
      </div>
      <!-- 主体 -->
      <div class="main">
        <!-- 标题 -->
        <div class="title">
          <h4>
            <nuxt-link class="active" to="/sign-in">
              登录
            </nuxt-link>
            <b>.</b>
            <nuxt-link class="hover" to="/sign-up">
            注册
           </nuxt-link>
          </h4>
        </div>
        <!-- form表单 -->
        <div class="js-form">
          <form method="post">
            <div class="input-prepend">
               <input type="text" class="input-prepend" placeholder="手机号或邮箱">
            <i class="fa fa-user"></i>
            </div>
           <div class="input-prepend">
             <input type="text" class="input-prepend" placeholder="密码">
            <i class="fa fa-lock"></i>
           </div>
            <div class="remember">
              <input type="checkbox">
            <span>记住我</span>
            </div>
            
            <nuxt-link class="help" to="/">登录遇到问题</nuxt-link>
            <button class="sign-in-btn">登录</button>
          </form>
        </div>
        <!-- 第三方 -->
        <div class="more-sign">
          <p class="">社交账号登录</p>
          <ul class="">
            <li>
              <nuxt-link to="/">
              <i class="fa fa-weixin"></i>
              </nuxt-link>
            </li>
               <li>
              <nuxt-link to="/">
              <i class="fa fa-weibo"></i>
              </nuxt-link>
            </li>
               <li>
              <nuxt-link to="/">
              <i class="fa fa-qq"></i>
              </nuxt-link>
            </li>
          </ul>
        </div>
      </div>
  </div>

</template>
<script>
export default {
  layout: 'sign',
  head: {
    title: "登录-简书",
    meta: [
      { charset: "utf-8" },
      { name: "keywords", content: "登录页面" },
      { name: "dscription", content: "登录简书" },
      { name: "author", content: "赵超" }
    ]
  },
  data() {
    return {};
  }
};
</script>
<style scoped>
  
</style>
