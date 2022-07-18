<template>
    <section id="imageType" v-bind:class=skill>
    <h2>포트폴리오가 실력이다.</h2>
    <p>이미지 유형입니다. 마우스 오버시 자세한 정보가 나와는 구조입니다.</p>
    <div class="image__inner container">
        <article class="image">
            <div class="image__header">
                <figure class="image__figure">
                    <img src="../assets/img/image_bg01.jpg" alt="애교만점 웰시코기"/>
                </figure>
            </div>
            <div class="image__body">
                <h3 class="image__title">애교만점 웰시코기</h3>
                <p class="image__desc">제목은 넥슨 풋볼 고딕 폰트입니다.<br/>설명부분은 넥슨 LV1 고딕 16px 140% 입니다.</p>
                <a href="/" class="image__btn">자세히 보기</a>
            </div>
        </article>
        <article class="image">
            <div class="image__header">
                <figure class="image__figure">
                    <img src="../assets/img/image_bg02.jpg" alt="코카스 파니엘"/>
                </figure>
            </div>
            <div class="image__body">
                <h3 class="image__title">코카스 파니엘</h3>
                <p class="image__desc">제목은 넥슨 풋볼 고딕 폰트입니다.<br/>설명부분은 넥슨 LV1 고딕 16px 140% 입니다.</p>
                <a href="/" class="image__btn yellow">자세히 보기</a>
            </div>
        </article>
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
.image__wrap {
    width: 100%;
    /* background: rgba(0,0,0,0.2); */
}
.image__inner {
    display: flex;
    justify-content: space-between;
}
.image__inner .image {
    width: 570px;
    position: relative;
}
.image__figure img {
    width: 100%;
    vertical-align: top;
}
.image__body {
    position: absolute;
    left: 30px;
    bottom: 30px;
    color: #fff;
    text-align: left;
}
.image__title {
    font-size: 32px;
    font-weight: 300;
    margin-bottom: 10px;
}
.image__desc {
    font-size: 16px;
    font-weight: 400;
    line-height: 140%;
    margin-bottom: 16px;
}
.image__btn {
    text-decoration: none;
    color: #fff;
    background: #BE4E15;
    padding: 10px 20px;
    display: inline-block;
}
.image__btn.yellow {
    background: #C9931D;
}
</style>