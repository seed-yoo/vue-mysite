<template>
  <div>
    <div id="wrap">
      
      <AppHeader />

      <div id="container" class="clearfix">
        <!-- aside 없음 -->
        <div id="full-content">
          <!-- content-head 없음 -->
          <div id="index">

            <img id="profile-img" src="@/assets/image/profile.jpg" />

            <div id="greetings">
              <p class="text-xlarge">
                <span class="bold">
                  안녕하세요!!<br />
                  황일영의 MySite에 오신 것을 환영합니다.<br />
                  <br />
                  이 사이트는 웹 프로그램밍 실습과제 예제 사이트입니다.<br />
                </span>
                <br />
                사이트 소개, 회원가입, 방명록, 게시판으로 구성되어 있으며<br />
                jsp&serlvet(모델2) 방식으로 제작되었습니다.<br />
                <br />
                자바 수업 + 데이터베이스 수업 + 웹프로그래밍 수업<br />
                배운 거 있는거 없는 거 다 합쳐서 만들어 놓은 사이트 입니다.<br />
                <br />
                (자유롭게 꾸며보세요!!)<br />
                <br /><br />
                <router-link class="" to="">[방명록에 글 남기기]</router-link>
              </p>
            </div>
            <!-- //greetings -->

            <div class="clear"></div>
          </div>
          <!-- //index -->
        </div>
        <!-- //full-content -->
      </div>
      <!-- //container -->

      <AppFooter />
      <!-- //footer -->
    </div>
    <!-- //wrap -->
  </div>
</template>

<script>
import "@/assets/css/main.css"

import AppFooter from "@/components/AppFooter.vue"
import AppHeader from "@/components/AppHeader.vue"

export default {
  name: "MainView",
  components: {
    AppFooter,
    AppHeader
  },
  data() {
    return {
      
    };
  },
  methods: {
    
  },
};
</script>

<style>
</style>