<script setup>
const name = {
    navItem: 'Item',
    navItem2: 'Item2',
    navItem3: 'Item3',
};
</script>

<template>
    <header class="header">
        <nav class="header__nav">
            <ul class="header__nav__list">
                <li class="header__nav__list_item">{{ name.navItem }}</li>
                <li class="header__nav__list_item">{{ name.navItem2 }}</li>
                <li class="header__nav__list_item">{{ name.navItem3 }}</li>
            </ul>
        </nav>
    </header>
</template>

<style scoped>
    .header {
        padding: 0 15px;
        height: 56px;
        border-bottom: 1px solid rgba(60, 60, 67, .5);
        box-sizing: border-box;
    }

    .header__nav,
    .header__nav__list  {
        display: flex;
        justify-content: center;
    }

    .header__nav__list_item {
        display: flex;
        align-items: center;
        margin-right: 10px;
        height: 56px;
        transition: color .3s;
        cursor: pointer;
    }

    .header__nav__list_item:hover {
        color: rgb(56 189 248);
    }
</style>