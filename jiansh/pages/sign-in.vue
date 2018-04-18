
<template>
    <div class="sign">
        <div class="logo">
            <nuxt-link to="/">
                <img src="../assets/img/logo.png">
            </nuxt-link>
        </div>

        <div class="main">
            <!-- title -->
            <div class="title">
                <h4>
                    <nuxt-link class="active" to="/sign-in">登录</nuxt-link>
                    <b>·</b>
                    <nuxt-link class to="/sign-up">注册</nuxt-link>
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
                    
                    <nuxt-link class="help" to="/">登录遇到问题？</nuxt-link>
                    <button>登录</button>
                </form>
            </div>
            <!-- 第三方登录 -->
            <div class="more-sign">
                <p>社交账号登录</p>
                <ul>
                    <li>
                        <nuxt-link to="/">
                            <i class="fa fa-weibo"></i>
                        </nuxt-link>
                    </li>
                    <li>
                        <nuxt-link to="/">
                            <i class="fa fa-weixin"></i>
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
// 修改当前页面的默认模板为sign.vue
// 如果不写的话，默认是default.vue

export default {
  layout: "sign",
  // 设置页面的标题，描述，关键字等信息
  head: {
    title: "登录-简书",
    meta: [
      { charset: "utf-8" },
      { name: "keywords", content: "登录页面" },
      { name: "discription", content: "登录简书" },
      { name: "author", content: "林鹏程" }
    ]
  },
  data() {}
};
</script>



