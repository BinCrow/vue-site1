<template>
        <section id="imgTextType" v-bind:class=skill>
    <h2 class="ir_so">이미지 텍스트 영역</h2>
    <div class="imgText__inner container">
        <div class="txt">
            <span class="small">이미지/텍스트 유형</span>
            <h3 class="title">유용한 사이트<br/>살펴보기</h3>
            <p class="desc">
                사이트 제작에 있어 이미지와
                텍스트를 혼합해서 사용하는 경우가 많다.<br/>
                기본 레이아웃은 동일하기 때문에
                이미지나 배치에 따라서
                느낌은 얼마든지 다르게 표현할 수 있다.<br/>
                Gmarket Sans 50px, Medium<br/>
                NEXON Lv1 Gothic 18px (153%)
            </p>
            <a href="/" class="btn">더 많은 유형 살펴보기</a>
        </div>
        <div class="img bg1"></div>
        <div class="img bg2"></div>
    </div>
</section>
</template>

<script>
export default {
    props: {
        skill:String,
    },
}
</script>


<style scoped>
.imgText__inner {
    display: flex;
    justify-content: space-between;
}
.imgText__inner > div {
    width: 32%;
    height: 500px;
}
.imgText__inner .txt {
    text-align: left;
}
.imgText__inner .txt span {
    display: inline-block;
    margin-bottom: 20px;
    text-decoration: underline;
    color: #777;
    font-size: 16px;
}
.imgText__inner .txt h3 {
    font-size: 50px;
    font-weight: 300;
    margin-bottom: 20px;
    line-height: 1.3;
}
.imgText__inner .txt p {
    color: #777;
    font-size: 16px;
    line-height: 1.5;
    padding-right: 20px;
    font-weight: 300;
    word-break: keep-all;
}
.imgText__inner .txt .btn {
    background: #000;
    color: #fff;
    display: inline-block;
    padding: 10px 30px;
    margin-top: 20px;
}
.imgText__inner .img {
    border-radius: 10px;
}
.imgText__inner .img.bg1 {
    background: url(../assets/img/imgText_bg01.jpg);
}
.imgText__inner .img.bg2 {
    background: url(../assets/img/imgText_bg02.jpg);
}
</style>