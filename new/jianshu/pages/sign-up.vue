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
            <nuxt-link class="hover" to="/sign-in">
              登录
            </nuxt-link>
            <b>.</b>
            <nuxt-link class="active" to="/sign-up">
            注册
           </nuxt-link>
          </h4>
        </div>
        <!-- form表单 -->
        <div class="js-form">
          <form method="post">
            <div class="input-prepend">
               <input type="text" class="input-prepend" placeholder="你的昵称">
            <i class="fa fa-user"></i>
            </div>
           <div class="input-prepend">
             <input type="text" class="input-prepend" placeholder="手机号">
            <i class="fa fa-phone "></i>
           </div>
           <div class="input-prepend ssm">
             <input type="text" name="" value="" placeholder="手机验证码">
             <i class="fa fa-shield"></i>
             <a href="#" class="send-ssm">发送验证码</a>
           </div>
          <div class="input-prepend">
            <input type="text" class="input-prepend" placeholder="密码">
            <i class="fa fa-lock"></i>
          </div>
            <button class="sign-up-btn">注册</button>
            <p class="sign-up-msg">
              点击 “注册” 即表示您同意并愿意遵守简书
              用户协议和隐私政策 。
            </p>
          </form>
        </div>
        <!-- 第三方 -->
        <div class="more-sign">
          <p class="">社交账号登录直接注册</p>
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
  head: {
    title: "注册-简书",
    meta: [
      { charset: "utf-8" },
      { name: "keywords", content: "注册页面" },
      { name: "dscription", content: "注册简书" },
      { name: "author", content: "赵超" }
    ]
  },
  data() {
    return {};
  }
};
</script>
