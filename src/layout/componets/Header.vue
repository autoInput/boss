<template>
  <div id="header">
    <div class="inner home-inner">
        <div class="logo">
            <a href="https://www.zhipin.com/" ka="header-home-logo" title="BOSS直聘"><span>BOSS直聘</span></a>
        </div>
        <div class="nav">
            <ul>
                <li class=""><a ka="header-home" href="https://www.zhipin.com/shenzhen/">首页</a></li>
                <li class="cur"><a ka="header-job" href="https://www.zhipin.com/job_detail/">职位</a></li>
                <li class=""><a ka="header_brand" href="https://www.zhipin.com/gongsi/">公司</a></li>
            </ul>
        </div>
        <div class="user-nav">
                <!--未登录-->
                <div class="btns">
                    <a href="https://www.zhipin.com/geek/attresume/parser.html" rel="nofollow" ka="nlp_resume_upload" class="link-sign-resume" title="上传简历，解析内容，完善注册">上传简历</a>
                    <a href="https://www.zhipin.com/geek/attresume/parser.html" rel="nofollow" ka="header-geek" class="link-sign-resume" title="上传简历，解析内容，完善注册">我要找工作<span class="new" style="display: inline;">hot</span></a>
                    <a href="https://signup.zhipin.com?intent=1" rel="nofollow" class="link-scan" ka="header-boss" title="我要招聘">我要招聘</a>
                    <a href="https://signup.zhipin.com" ka="header-register" class="btn btn-outline">注册</a>
                    <a href="https://login.zhipin.com" ka="header-login" class="btn btn-outline">登录</a>
                </div>
        </div>
    </div>
<div class="school-nav-box"><a href="/xiaoyuan/"><div class="img-box xiaoyuan"></div></a><a href="/xiaoyuan/renshebu/"><div class="img-box renshebu"></div></a><a href="/xiaoyuan/yangshi/"><div class="img-box yangshi"></div></a><a href="/xiaoyuan/fupin/"><div class="img-box fupin"></div></a></div></div>
</template>

<script>
export default {

}
</script>

<style lang="scss">
@import '~@/assets/css/main.scss';
#header .school-nav-box {
  width: 450px;
  padding: 5px;
  position: absolute;
  background-color: #fff;
  box-shadow: 0 2px 8px 0 rgba(0, 0, 0, .15);
  display: none
}

#header .school-nav-box::before {
  content: '';
  position: absolute;
  width: 27px;
  height: 15px;
  left: 0;
  right: 0;
  top: -15px;
  margin: auto;
  /* //background-image: url(../images/icon/dialog-arrow-up.png) */
}

#header .school-nav-box .img-box {
  height: 92px
}

#header .school-nav-box .img-box.xiaoyuan {
  margin-bottom: 5px;
  /* //background-image: url../images/banner-xiaoyuan.jpg) */
}

#header .school-nav-box .img-box.renshebu {
  margin-bottom: 5px;
  /* //background-image: url../images/banner-minying.jpg) */
}

#header .school-nav-box .img-box.yangshi {
  margin-bottom: 5px;
  /* //background-image: url../images/banner-yangshi_v2.jpg) */
}

#header .school-nav-box .img-box.fupin {
  margin-bottom: 0;
  /*  */
  background-size: 100% 100%
}
</style>