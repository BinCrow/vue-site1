<template>
        <header id="headerType">
        <div class="header__inner">
        <h1 class="header__logo">
            <a href="/">WEB <em>site</em></a>
        </h1>
        <nav class="header__menu">
            <h2 class="ir_so">메인 메뉴</h2>
            <ul>
            <li>
                <a href="/">헤더 영역</a>
            </li>
            <li>
                <a href="/">슬라이드 영역</a>
            </li>
            <li>
                <a href="/">이미지 영역</a>
            </li>
            <li>
                <a href="/">컨텐츠 영역</a>
            </li>
            <li>
                <a href="/">푸터 영역</a>
            </li>
            </ul>
        </nav>
        <div className="header__member">
            <a href="/">로그인</a>
        </div>
        </div>
    </header>
</template>

<style scoped>
.header__inner {
    display: flex;
    align-items: center;
    justify-content: space-between;
    border-bottom: 1px solid #ccc;
    padding: 0 20px;
}
.header__logo {
    flex-basis: 20%;
}
.header__logo a {
    font-size: 30px;
    display: inline-block;
    padding: 5px;
}
.header__logo em {
    font-size: 18px;
    font-weight: 300;
    text-transform: uppercase;
}
.header__menu {
    flex-basis: 60%;
    text-align: center;
}
.header__menu ul {
    padding: 25px;
}
.header__menu li {
    display: inline;
}
.header__menu li a {
    padding: 15px 30px;
    transition: background 0.3s;
}
.header__menu li a:hover {
    background: #f1f1f1;
    border-radius: 5px;
}
.header__member {
    flex-basis: 20%;
    text-align: right;
}
.header__member a {
    border-radius: 50px;
    border: 1px solid #000;
    padding: 9px 24px 8px;
}
</style>