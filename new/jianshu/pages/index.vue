<template>
  <div style="">
  <my-header></my-header>
  <div class="container index">
    <div class="row">
      <div class="col-xs-16 main">
        <!-- 热门专题 -->
        <div class="recommend-collection">
          <nuxt-link to="collection/123" class="collection">
            <img src="~/assets/img/cone.jpg" alt="">
            <span>手绘</span>
          </nuxt-link>
          <nuxt-link to="collection/123" class="collection">
            <img src="~/assets/img/ctwo.jpg" alt="">
            <span>读书</span>
          </nuxt-link>
          <nuxt-link to="collection/123" class="collection">
            <img src="~/assets/img/cthree.jpg" alt="">
            <span>社会热点</span>
          </nuxt-link>
          <nuxt-link to="collection/123" class="collection">
            <img src="~/assets/img/cfour.jpg" alt="">
            <span>IT_互联网</span>
          </nuxt-link>
          <nuxt-link to="collection/123" class="collection">
            <img src="~/assets/img/cfive.png" alt="">
            <span>旅行·在路上</span>
          </nuxt-link>
          <nuxt-link class="more-collection" to="collection/123">
            更多热门专题
            <i class="fa fa-angle-right"></i>
          </nuxt-link>
        
        
        </div>

        <div class="split-line"></div>

        <!-- 文章列表 -->
        <div class="list-container">
          <ul class="note-list">
            <li class="have-img">
              <nuxt-link to="/p/123" class="wrap-img">
              <img src="~/assets/img/lock.png" alt=""></nuxt-link>
              <div class="content">
                <div class="author">
                  <nuxt-link to="/p/123" class="avatar">
                    <img src="~/assets/img/default-avatar.jpg" alt="">
                  </nuxt-link>
                  <div class="info">
                  <nuxt-link to="/u/123" class="nickname">测试用户
                  </nuxt-link>
                  <span class="time">04.12 10:18</span>
                  </div>
                </div>
                <nuxt-link to="/p/123" class="title">你为什么至今单身？看完后扎心了！</nuxt-link>
                <div class="abstruct">
                  文/麦大人 01 知乎上有个热门话题：为什么现在的男性普遍不再对女性展开追求了？ 下面留言竟有24591个回答，看得出大家对这个话题的感兴趣程度。 如今，单身贵族越来越多，当...
                </div>
                <div class="meta">
                  <nuxt-link to="/c/123" class="collection-tag">
                    社会热点
                  </nuxt-link>
                  <nuxt-link to="/p/123">
                    <i class="fa fa-eye"></i>1500
                  </nuxt-link>
                  <nuxt-link to="/p/123">
                    <i class="fa fa-comment"></i>100
                  </nuxt-link>
                  <span><i class="fa fa-heart"></i>10</span>
                </div>
              </div>
            </li>

              <div class="content">
                <div class="author">
                  <nuxt-link to="/p/123" class="avatar">
                    <img src="~/assets/img/default-avatar.jpg" alt="">
                  </nuxt-link>
                  <div class="info">
                  <nuxt-link to="/u/123" class="nickname">测试用户
                  </nuxt-link>
                  <span class="time">04.12 10:18</span>
                  </div>
                </div>
                <div class="title">你为什么至今单身？看完后扎心了！</div>
                <div class="abstruct">
                  文/麦大人 01 知乎上有个热门话题：为什么现在的男性普遍不再对女性展开追求了？ 下面留言竟有24591个回答，看得出大家对这个话题的感兴趣程度。 如今，单身贵族越来越多，当...
                </div>
                <div class="meta">
                  <nuxt-link to="/p/123">
                    <i class="fa fa-eye"></i>1500
                  </nuxt-link>
                  <nuxt-link to="/p/123">
                    <i class="fa fa-comment"></i>100
                  </nuxt-link>
                  <span><i class="fa fa-heart"></i>10</span>
                </div>
              </div>

              <li class="have-img">
              <nuxt-link to="/p/123" class="wrap-img">
              <img src="~/assets/img/lock.png" alt=""></nuxt-link>
              <div class="content">
                <div class="author">
                  <nuxt-link to="/p/123" class="avatar">
                    <img src="~/assets/img/default-avatar.jpg" alt="">
                  </nuxt-link>
                  <div class="info">
                  <nuxt-link to="/u/123" class="nickname">测试用户
                  </nuxt-link>
                  <span class="time">04.12 10:18</span>
                  </div>
                </div>
                <nuxt-link to="/p/123" class="title">你为什么至今单身？看完后扎心了！</nuxt-link>
                <div class="abstruct">
                  文/麦大人 01 知乎上有个热门话题：为什么现在的男性普遍不再对女性展开追求了？ 下面留言竟有24591个回答，看得出大家对这个话题的感兴趣程度。 如今，单身贵族越来越多，当...
                </div>
                <div class="meta">
                  <nuxt-link to="/c/123" class="collection-tag">
                    社会热点
                  </nuxt-link>
                  <nuxt-link to="/p/123">
                    <i class="fa fa-eye"></i>1500
                  </nuxt-link>
                  <nuxt-link to="/p/123">
                    <i class="fa fa-comment"></i>100
                  </nuxt-link>
                  <span><i class="fa fa-heart"></i>10</span>
                </div>
              </div>
            </li>
              <div class="content">
                <div class="author">
                  <nuxt-link to="/p/123" class="avatar">
                    <img src="~/assets/img/default-avatar.jpg" alt="">
                  </nuxt-link>
                  <div class="info">
                  <nuxt-link to="/u/123" class="nickname">测试用户
                  </nuxt-link>
                  <span class="time">04.12 10:18</span>
                  </div>
                </div>
                <div class="title">你为什么至今单身？看完后扎心了！</div>
                <div class="abstruct">
                  文/麦大人 01 知乎上有个热门话题：为什么现在的男性普遍不再对女性展开追求了？ 下面留言竟有24591个回答，看得出大家对这个话题的感兴趣程度。 如今，单身贵族越来越多，当...
                </div>
                <div class="meta">
                  <nuxt-link to="/p/123">
                    <i class="fa fa-eye"></i>1500
                  </nuxt-link>
                  <nuxt-link to="/p/123">
                    <i class="fa fa-comment"></i>100
                  </nuxt-link>
                  <span><i class="fa fa-heart"></i>10</span>
                </div>
              </div>

          </ul>

        </div>


    <a href="#" class="load-more">阅读更多</a>

      </div>


      <div class="col-xs-offset-1 col-xs-7 aside">
        <div class="row">
          <div class="board">
          <nuxt-link to="/">
            <img src="~assets/img/a1.png" alt="">
          </nuxt-link>
          <nuxt-link to="/">
            <img src="~assets/img/a2.png" alt="">
          </nuxt-link>
          <nuxt-link to="/">
            <img src="~assets/img/a3.png" alt="">
          </nuxt-link>
          <nuxt-link to="/">
            <img src="~assets/img/a4.png" alt="">
          </nuxt-link>
        </div>

        <div class="recommended-author">
          <div class="title">
            <span>推荐作者</span>
            <nuxt-link to="/" class="page-change">
              <i class="fa fa-refresh"></i>换一批
            </nuxt-link>
          </div>
          <ul class="recommended-list">
            <li>
              <nuxt-link class="avatar" to="/u/123">
                <img src="~/assets/img/default-avatar.jpg" alt="">
              </nuxt-link>
              <a href="#" class="follow">
                <i class="fa fa-plus"></i>关注
              </a>
              <nuxt-link to="/u/123" class="name">简书用户

              </nuxt-link>
              <p>写了506.7K字·800喜欢</p>

            </li>
             <li>
              <nuxt-link class="avatar" to="/u/123">
                <img src="~/assets/img/default-avatar.jpg" alt="">
              </nuxt-link>
              <a href="#" class="follow">
                <i class="fa fa-plus"></i>关注
              </a>
              <nuxt-link to="/u/123" class="name">简书用户

              </nuxt-link>
              <p>写了506.7K字·800喜欢</p>

            </li>
             <li>
              <nuxt-link class="avatar" to="/u/123">
                <img src="~/assets/img/default-avatar.jpg" alt="">
              </nuxt-link>
              <a href="#" class="follow">
                <i class="fa fa-plus"></i>关注
              </a>
              <nuxt-link to="/u/123" class="name">简书用户

              </nuxt-link>
              <p>写了506.7K字·800喜欢</p>

            </li>
             <li>
              <nuxt-link class="avatar" to="/u/123">
                <img src="~/assets/img/default-avatar.jpg" alt="">
              </nuxt-link>
              <a href="#" class="follow">
                <i class="fa fa-plus"></i>关注
              </a>
              <nuxt-link to="/u/123" class="name">简书用户

              </nuxt-link>
              <p>写了506.7K字·800喜欢</p>

            </li>
             <li>
              <nuxt-link class="avatar" to="/u/123">
                <img src="~/assets/img/default-avatar.jpg" alt="">
              </nuxt-link>
              <a href="#" class="follow">
                <i class="fa fa-plus"></i>关注
              </a>
              <nuxt-link to="/u/123" class="name">简书用户

              </nuxt-link>
              <p>写了506.7K字·800喜欢</p>

            </li>
          </ul>
          <nuxt-link to="/" class="find-more">查看更多
            <i class="fa fa-angle-right"></i>
          </nuxt-link>
        </div>

        </div>

      </div>
    </div>


  </div>
  </div>
</template>
<script>
import myHeader from "../components/myHeader.vue";
export default {
  head: {
    title: "简书-创作你的创作",
    meta: [
      { charset: "utf-8" },
      { name: "keywords", content: "简书首页" },
      { name: "dscription", content: "简书首页" },
      { name: "author", content: "林鹏程" }
    ]
  },
  components: {
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

