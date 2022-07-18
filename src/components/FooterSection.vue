<template>
    <footer id="footerType">
    <h2 class="ir_so">푸터 영역</h2>
    <div class="footer__inner container">
        <div class="footer__menu">
            <div>
                <h3>레이아웃 영역</h3>
                <ul>
                    <li><a href="/">레이아웃 유형01</a></li>
                    <li><a href="/">레이아웃 유형02</a></li>
                    <li><a href="/">레이아웃 유형03</a></li>
                    <li><a href="/">레이아웃 유형04</a></li>
                    <li><a href="/">레이아웃 유형05</a></li>
                </ul>
            </div>
            <div>
                <h3>헤더 영역</h3>
                <ul>
                    <li><a href="/">메뉴 유형01</a></li>
                </ul>
            </div>
            <div>
                <h3>메인 영역</h3>
                <ul>
                    <li><a href="/">이미지 유형01</a></li>
                    <li><a href="/">동영상 유형02</a></li>
                    <li><a href="/">슬라이드 유형03</a></li>
                </ul>
            </div>
            <div>
                <h3>컨텐츠 영역</h3>
                <ul>
                    <li><a href="/">텍스트 유형01</a></li>
                    <li><a href="/">이미지 유형02</a></li>
                    <li><a href="/">이미지/텍스트03</a></li>
                    <li><a href="/">카드 유형04</a></li>
                    <li><a href="/">배너 유형05</a></li>
                </ul>
            </div>
            <div>
                <h3>푸터 영역</h3>
                <ul>
                    <li><a href="/">컨택트 유형01</a></li>
                    <li><a href="/">푸터 유형02</a></li>
                </ul>
            </div>
            <div>
                <h3>사이트 영역</h3>
                <ul>
                    <li><a href="/">웹표준 사이트</a></li>
                    <li><a href="/">반응형 사이트</a></li>
                    <li><a href="/">패럴랙스 사이트</a></li>
                    <li><a href="/">포트폴리오 사이트</a></li>
                </ul>
            </div>
        </div>
        <address class="footer__right">
            ©2022 webstroyboy. All rights reserved.
        </address>
    </div>
    </footer>
</template>

<style scoped>
.footer__menu {
    display: flex;
    justify-content: space-between;
}
.footer__menu > div {
    width: 16%;
    text-align: left;
}
.footer__menu > div h3 {
    font-size: 22px;
    font-weight: 500;
    margin-bottom: 20px;
}
.footer__menu > div li a {
    font-size: 16px;
    line-height: 1.6;
    color: #777;
    font-weight: 300;
}
.footer__right {
    border-top: 1px solid #ccc;
    margin-top: 50px;
    padding-top: 50px;
}
</style>