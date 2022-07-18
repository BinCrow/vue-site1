<template>
    <section id="bannerType" class="banner__wrap">
    <h2 class="ir_so">배너 영역</h2>
    <div class="banner__inner">
        <h3 class="banner__title">유튜버 웹보이</h3>
        <p class="banner__desc">
            더 다양한 강의는 유튜브를 통해 제공하고 있습니다.
            <a href="/">youtube.com/c/Webstoryboy</a>
        </p>
        <span class="banner__sub">배너 영역01</span>
    </div>
  </section>
</template>

<style scoped>
.banner__wrap {
    background-image: url(../assets/img/banner_bg01@2x.jpg);
    background-position: center center;
    background-size: cover;
    background-repeat: no-repeat;
}
.banner__inner {
    text-align: center;
    color: #fff;
}
.banner__title {
    font-size: 50px;
    font-weight: 300;
    margin-bottom: 40px;
}
.banner__desc {
    font-size: 24px;
    line-height: 1.5;
    font-weight: 300;
    margin-bottom: 70px;
}
.banner__desc a {
    display: block;
    font-size: 24px;
    line-height: 1.5;
    font-weight: 300;
    color: #fff;
    text-decoration: none;
    margin-bottom: 70px;
}
.banner__sub {
    font-size: 16px;
    font-weight: 300;
    text-decoration: underline;
    text-underline-position: under;
}
</style>