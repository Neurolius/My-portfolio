<div class="hotel">

<span class="head">
    <div class="header">
        <div class="logo"><img src="/img/logo-min.png" alt="logo"></div>
    </div>
    <div class="menu-main">
        <ul class="menu">
            <li class="menu-item"><a href="#">УСЛОВИЯ ПРОЖИВАНИЯ </a> </li>

            <li class="menu-item"><a href=".#"> КОНТАКТНАЯ ИНФОРМАЦИЯ</a> </li>
        </ul>

        <ul class="menu">
            <li class="menu-item"><a href="#">НОМЕРА</a> </li>
            <li class="menu-item"><a href="#"> ЦЕНЫ</a></li>
        </ul>
    </div>
</span>

<div class="main-text">
    <p class="menu-main">
        ЛУЧШЕЕ МЕСТО ДЛЯ <br> ВАШЕГО ОТДЫХА
    </p>
</div>



<div class="but">
    
    <img src="/img/icon.svg" alt="" height="80px" width="80px" class="icon">
    <button class="button">
        ЗАБРОНИРОВАТЬ
    </button>
</div>
</div>
<h3 align="center">Для дальнейшего изучения сайта вы можете скачать архив с кодом и сами добавить что-то своё
    и разобраться с кодом. Для этого нажмите на кнопку ниже.
</h3>
<a href="/file_to_downoload/site_2.rar" download="" class="butt">
    <button >
        Скачать архив 
    </button>
</a>
<style>
    .butt{
        display:flex;
        justify-content: center;
    }
    .hotel{
    max-width: 1280px;
    width: 100%;
    
    background: url('/img/background.png') no-repeat;
    height: 100%;
    color: #fff;
}

.logo {
    background-color: #6E4422;
}

.menu {
    display: flex;
    justify-content: space-around;
}

.head {
    display: flex;
    justify-content: space-around;
    
}

.main-text {
    margin-left: 28px;

}

li:not(last-child) {
    margin-right: 30px;
}

.menu-item {
    list-style-type: none;
}

.menu-item a {
    text-decoration: none;
    color: white;

}

.button {
    all: unset;
    padding: 22px 55px;
    background: #f6762c;
    border-radius: 50px;
    color: #fff;
    font-weight: 500;
    font-size: 16px;
    line-height: 50px;

    margin-top: 50px;
}

@media screen and (max-width: 480px) {
    .head {
        flex-wrap: wrap;
        width: 95%;
        /* ширина карточки 95% от ширины контейнера */
    }
    
    .hotel{
        max-width: 1280px;
        width: 100%;
    
        background: url('/img/background.png') no-repeat;
        background-size: 1280px 1280px;
        height: 100%;
        color: #fff;
    }
}
</style>