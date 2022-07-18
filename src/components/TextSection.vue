<template>
        <section id="textType" class="text__wrap section nexon">
    <h2>코딩과 관련된 직업</h2>
    <p>너무 무리하지 말아요! 이미 당신은 해내고 있고 앞으로도 잘 할 수 있을거예요! </p>
    <div class="text__inner container">
        <div class="text">
            <h3>웹 디자인</h3>
            <p>웹디자이너가 포함된 웹 및 멀티미디어 디자이너는 다른 직업과 비교하여 임금과 복리후생이 낮은 편이다.</p>
        </div>
        <div class="text">
            <h3>웹 퍼블리셔</h3>
            <p>퍼블리싱은 웹 사이트를 제작할 때, 웹 디자이너가 디자인한 것을 웹 표준성과 접근성에 부합하도록 재정</p>
        </div>
        <div class="text">
            <h3>프론트앤드 개발자</h3>
            <p>사이트와 상호작용하는 모든 부분에 대한 개발, 관리, 유지 보수를 하는 것 솔루션의 프로세스</p>
        </div>
        <div class="text">
            <h3>백앤드 개발자</h3>
            <p>용어 자체에서 알 수 있듯이, 백엔드는 웹사이트나 웹 애플리케이션 또는 모바일 솔루션의 프로세스와 관련된입니다.</p>
        </div>
        <div class="text">
            <h3>웹 디자인</h3>
            <p>웹디자이너가 포함된 웹 및 멀티미디어 디자이너는 다른 직업과 비교하여 임금과 복리후생이 낮은 편이다.</p>
        </div>
        <div class="text">
            <h3>웹 퍼블리셔</h3>
            <p>퍼블리싱은 웹 사이트를 제작할 때, 웹 디자이너가 디자인한 것을 웹 표준성과 접근성에 부합하도록 재정</p>
        </div>
    </div>
</section>
</template>

<style scoped>
.text__inner {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    text-align: left;
}
.text__inner .text {
    width: 31%;
}
.text__inner .text:nth-child(1),
.text__inner .text:nth-child(2),
.text__inner .text:nth-child(3) {
    margin-bottom: 70px;
}
.text__inner .text h3 {
    font-size: 24px;
    font-weight: 500;
    margin-bottom: 10px;
    padding-top: 60px;
    position: relative;
}
.text__inner .text h3::before {
    content: '';
    width: 50px;
    height: 50px;
    border-radius: 50%;
    position: absolute;
    left: 0; top: 0;
    background-image: url(../assets/img/text_bg01.svg);
    background-size: 160px;
}
.text__inner .text:nth-child(1) h3::before {
    background-position: 5px 5px;
    background-color: #D3D8FA;
}
.text__inner .text:nth-child(2) h3::before {
    background-position: -36px 5px;
    background-color: #CEF6EE;
}
.text__inner .text:nth-child(3) h3::before {
    background-position: -75px 5px;
    background-color: #F6F4E0;
}
.text__inner .text:nth-child(4) h3::before {
    background-position: -115px 5px;
    background-color: #F8D1D8;
}
.text__inner .text:nth-child(5) h3::before {
    background-position: -115px 5px;
    background-color: #F8D1D8;
}
.text__inner .text:nth-child(6) h3::before {
    background-position: -115px 5px;
    background-color: #F8D1D8;
}
.text__inner .text p {
    font-size: 16px;
    font-weight: 300;
    line-height: 1.6;
    text-align: justify;
}
</style>