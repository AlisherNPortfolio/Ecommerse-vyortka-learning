<template>
    <header class="header">
        <div class="header__line-top">
            <div class="container">
                <div class="sale__box-right">
                    <span>Black</span>
                    <b>Friday</b>
                </div>
                <div class="sale__box-center">
                    <span>Up to</span>
                    <b>59%</b>
                    OFF
                </div>
                <a class="shop__now-btn btn">
                    Shop now
                    <font-awesome-icon icon="fa-solid fa-arrow-right" />
                </a>
            </div>
        </div>
        <div class="header__line-middle">
            <div class="header__line-greeting">
                <span>Welcome to Clicon online eCommerce store</span>
            </div>
            <div class="header__middle-line-right">
                <div class="header__line-socials">
                    <span>Follow us:</span>
                    <font-awesome-icon icon="fa-brands fa-twitter" />
                    <font-awesome-icon icon="fa-brands fa-facebook" />
                    <font-awesome-icon icon="fa-brands fa-pinterest" />
                    <font-awesome-icon icon="fa-brands fa-reddit" />
                    <font-awesome-icon icon="fa-brands fa-youtube" />
                    <font-awesome-icon icon="fa-brands fa-instagram" />
                </div>
                <div class="header__middle-dropdowns">
                    <div class="header__middle-langs">
                        <div class="lang-container">
                            <div class="lang-active">
                                <span>En</span>
                                <font-awesome-icon icon="fa-solid fa-chevron-down" />
                            </div>
                            <div class="lang-list">
                                <div class="lang-item">
                                    <a href="#">Uz</a>
                                </div>
                                <div class="lang-item">
                                    <a href="#">En</a>
                                </div>
                                <div class="lang-item">
                                    <a href="#">Ru</a>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="header__middle-currencies">
                        <div class="currency-container">
                            <div class="currency-active">
                                <span>USD</span>
                                <font-awesome-icon icon="fa-solid fa-chevron-down" />
                            </div>
                            <div class="currency-list">
                                <div class="currency-item">
                                    <a href="#">UZS</a>
                                </div>
                                <div class="currency-item">
                                    <a href="#">USD</a>
                                </div>
                                <div class="currency-item">
                                    <a href="#">RUB</a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="header__line-bottom">
            <div class="logo-container">
                <img src="~/assets/img/logo.png" alt="logo">
            </div>
            <div class="header__search-box">
                <form>
                    <input type="text" placeholder="Search for anything">
                    <button class="search-btn">
                        <font-awesome-icon icon="fa-solid fa-search" />
                    </button>
                </form>
            </div>
            <div class="header__line-bottom-right">
                <div class="header__cart-item">
                    <font-awesome-icon icon="fa-solid fa-cart-shopping" />
                    <span>2</span>
                </div>
                <font-awesome-icon icon="fa-regular fa-heart" />
                <font-awesome-icon icon="fa-regular fa-user" />
            </div>
        </div>
        <div class="header__line-menu">
            <div class="container">
            </div>
        </div>
    </header>
</template>
<script setup lang="ts"></script>