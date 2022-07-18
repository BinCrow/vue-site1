<template>
        <section id="cardType" v-bind:class=skill>
    <h2>웹스토리보이 강의</h2>
    <p>
        웹디자이너, 웹 퍼블리셔, 프론트앤드 개발자를 위한 강의 사이트입니다.<br/> 
        Gmarket Sans Light 22px 150% #67778A 
    </p>
    <div class="card__inner container">
        <article class="card">
            <figure class="card__header">
                <img class="img" src="../assets/img/card_bg01.jpg" alt="이미지1"/>
            </figure>
            <div class="card__body">
                <h3 class="title">웹표준 사이트 만들기</h3>
                <p class="desc">사이트를 만들기 위한 기초 강의입니다. 기본 코딩에 대한 감각을 익히고, 웹 표준을 준수하면서 코딩하는 방법을 익힙니다. 다양한 예제를 통해 사이트를 만드는 기본 강의입니다.</p>
                <a class="btn" href="#">
                    더 자세히 보기
                    <svg width="52" height="8" viewBox="0 0 52 8" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path d="M51.3536 4.35355C51.5488 4.15829 51.5488 3.84171 51.3536 3.64645L48.1716 0.464466C47.9763 0.269204 47.6597 0.269204 47.4645 0.464466C47.2692 0.659728 47.2692 0.976311 47.4645 1.17157L50.2929 4L47.4645 6.82843C47.2692 7.02369 47.2692 7.34027 47.4645 7.53553C47.6597 7.7308 47.9763 7.7308 48.1716 7.53553L51.3536 4.35355ZM0 4.5H51V3.5H0V4.5Z" fill="#5B5B5B"/>
                    </svg>
                </a>
            </div>
        </article>
        <article class="card">
            <figure class="card__header">
                <img class="img" src="../assets/img/card_bg02.jpg" alt="이미지2"/>
            </figure>
            <div class="card__body">
                <h3 class="title">웹표준 사이트 만들기</h3>
                <p class="desc">사이트를 만들기 위한 기초 강의입니다. 기본 코딩에 대한 감각을 익히고, 웹 표준을 준수하면서 코딩하는 방법을 익힙니다. 다양한 예제를 통해 사이트를 만드는 기본 강의입니다.</p>
                <a class="btn" href="/">
                    더 자세히 보기
                    <svg width="52" height="8" viewBox="0 0 52 8" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path d="M51.3536 4.35355C51.5488 4.15829 51.5488 3.84171 51.3536 3.64645L48.1716 0.464466C47.9763 0.269204 47.6597 0.269204 47.4645 0.464466C47.2692 0.659728 47.2692 0.976311 47.4645 1.17157L50.2929 4L47.4645 6.82843C47.2692 7.02369 47.2692 7.34027 47.4645 7.53553C47.6597 7.7308 47.9763 7.7308 48.1716 7.53553L51.3536 4.35355ZM0 4.5H51V3.5H0V4.5Z" fill="#5B5B5B"/>
                    </svg>
                </a>
            </div>
        </article>
        <article class="card">
            <figure class="card__header">
                <img class="img" src="../assets/img/card_bg03.jpg" alt="이미지3"/>
            </figure>
            <div class="card__body">
                <h3 class="title">웹표준 사이트 만들기</h3>
                <p class="desc">사이트를 만들기 위한 기초 강의입니다. 기본 코딩에 대한 감각을 익히고, 웹 표준을 준수하면서 코딩하는 방법을 익힙니다. 다양한 예제를 통해 사이트를 만드는 기본 강의입니다.</p>
                <a class="btn" href="#">
                    더 자세히 보기
                    <svg width="52" height="8" viewBox="0 0 52 8" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path d="M51.3536 4.35355C51.5488 4.15829 51.5488 3.84171 51.3536 3.64645L48.1716 0.464466C47.9763 0.269204 47.6597 0.269204 47.4645 0.464466C47.2692 0.659728 47.2692 0.976311 47.4645 1.17157L50.2929 4L47.4645 6.82843C47.2692 7.02369 47.2692 7.34027 47.4645 7.53553C47.6597 7.7308 47.9763 7.7308 48.1716 7.53553L51.3536 4.35355ZM0 4.5H51V3.5H0V4.5Z" fill="#5B5B5B"/>
                    </svg>
                </a>
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
.card__inner {
    display: flex;
    justify-content: space-between;
}
.card {
    width: 32%;
}
.card__body {
    padding: 24px;
    background: #f5f5f5;
    text-align: left;
}
.card__body .title {
    font-size: 24px;
    font-weight: 500;
    margin-bottom: 10px;
}
.card__body .desc {
    font-size: 16px;
    line-height: 1.5;
    color: #5b5b5b;
    font-weight: 300;
    margin-bottom: 20px;
    overflow: hidden;
    text-overflow: ellipsis;
    display: -webkit-box;
    -webkit-line-clamp: 4; 
    -webkit-box-orient: vertical;
    word-break: keep-all;
}

</style>