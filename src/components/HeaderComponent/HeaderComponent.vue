<script setup lang='ts'>
import './header-component.css';
import LogoIcon from '../icons/LogoIcon.vue';
import SearchIcon from '../icons/SystemicIcon/SearchIcon.vue';

</script>

<template>
   <header class="header">
        <div class="header--bg"></div>
        <div class="header--wrapper">
            <a href="#" class="header--logo-link">
                <LogoIcon class="header--logo"/>
            </a>
            <nav class="header--nav">   
            <ul class="header--list">
                <li class="header--item">
                     <a href="#" class="header--item-link"> Главная</a>
                </li>
                <li class="header--item">
                     <a href="#" class="header--item-link"> О нас</a>
                </li>
                <li class="header--item">
                     <a href="#" class="header--item-link"> Услуги</a>
                </li>
                <li class="header--item">
                     <a href="#" class="header--item-link"> Кейсы</a>
                </li>
                <li class="header--item">
                     <a href="#" class="header--item-link"> Блог</a>
                </li>
                <li class="header--item">
                     <a href="#" class="header--item-link"> Контакты</a>
                </li>
            </ul>
        </nav>
        <a href="tel:+7 (989) 222-44-22" class="header--number">+7 (989) 222-44-22</a>
        <div class="header--inner">
            <button class="header--search-button"> <SearchIcon class="header--search"/> </button>
            <button class="header--dropdown-trigger">
                <div class="header--dropdown-trigger-wrapper">
                    <div class="dropwodn-trigger--item"></div>
                     <div class="dropwodn-trigger--item"></div>
                    <div class="dropwodn-trigger--item"></div>
                    <div class="dropwodn-trigger--item"></div>
                </div>
            </button>
        </div>
    </div>
   </header>
</template>