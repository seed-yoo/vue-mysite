<template>
  <div>
    <div id="wrap">
        <AppHeader />

      <div id="container" class="clearfix">
        <div id="aside">
          <h2>회원</h2>
          <ul>
            <li>회원정보</li>
            <li>로그인</li>
            <li>회원가입</li>
          </ul>
        </div>
        <!-- //aside -->

        <div id="content">
          <div id="content-head">
            <h3>회원가입</h3>
            <div id="location">
              <ul>
                <li>홈</li>
                <li>회원</li>
                <li class="last">회원가입</li>
              </ul>
            </div>
            <div class="clear"></div>
          </div>
          <!-- //content-head -->

          <div id="user">
            <div id="joinOK">
              <p class="text-large bold">
                회원가입을 축하합니다.<br />
                <br />
                <router-link class="btn_s" to="/user/loginform">[로그인하기]</router-link>
              </p>
            </div>
            <!-- //joinOK -->
          </div>
          <!-- //user -->
        </div>
        <!-- //content  -->
      </div>
      <!-- //container  -->

      <AppFooter />
      <!-- //footer -->
    </div>
    <!-- //wrap -->
  </div>
</template>


<script>
import "@/assets/css/user.css";
import AppFooter from "@/components/AppFooter.vue";
import AppHeader from "@/components/AppHeader.vue";

export default {
  name: "JoinOkView",
  components: {
    AppFooter,
    AppHeader
  },
  data() {
    return {};
  },
  methods: {},
};
</script>


<style></style>