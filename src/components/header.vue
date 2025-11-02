<template>
  <header class="background-color-white display-flex-row-center-center">
    <nav class="display-flex-row-space-between-center">
                <a href="#">
                    <!-- logo image 220 x 86 -->
                    <img src="@/assets/images/logo.svg" alt="logo" class="logo" />
                </a>
                <ul class="display-flex-row-center-center">
                    <li class="text-color-primary" v-for="title in titles">
                        <a href="#" class="text-medium-16px">{{ title }}</a>
                    </li>

                </ul>
                <ul class="display-flex-row-center-center">
                    <li class="menu-search">
                        <div
                            class="icon background-color-primary"
                            style="mask-image: url('/src/assets/icons/icon-search.svg'); width: 26px; height: 26px"></div>
                        <!-- display-none -->
                        <input
                            type="text"
                            class="menu-search-input text-regular-14px background-color-white text-color-primary border-radius-8px border-2px-light display-none"
                            placeholder="Search..." />
                        <!-- add search button -->
                    </li>
                    <li class="text-bold-16px text-color-primary menu-language">
                        AZ
                        <!-- display-none -->
                        <div
                            class="menu-language-dropdown background-color-white border-radius-8px border-2px-light display-none">
                            <div class="menu-language-dropdown-item text-color-primary">AZ</div>
                            <div class="menu-language-dropdown-item text-color-primary">EN</div>
                            <div class="menu-language-dropdown-item text-color-primary">RU</div>
                        </div>
                    </li>
                    <li class="menu-account">
                        <!-- display-none -->
                        <div
                            class="icon background-color-primary"
                            style="mask-image: url('src/assets/icons/icon-login.svg'); width: 26px; height: 26px"></div>
                        <div
                            class="menu-account-dropdown background-color-white border-radius-8px border-2px-light display-none">
                            <!-- add icons to these elements -->
                            <div class="menu-account-dropdown-item text-color-primary">Səbət</div>
                            <div class="menu-account-dropdown-item text-color-primary">Tənzimləmələr</div>
                            <div class="menu-account-dropdown-item text-color-primary">Şifrəni dəyiş</div>
                            <div class="menu-account-dropdown-item text-color-primary">Çıxış</div>
                            <div class="menu-account-dropdown-item text-color-primary">Giriş</div>
                            <div class="menu-account-dropdown-item text-color-primary">Qeydiyyat</div>
                        </div>
                    </li>
                </ul>
            </nav>
  </header>
</template>

<script>

export default{
    data(){
        return{
            titles: ["Əsas səhifə" , "Haqqımızda", "Xidmətlərimiz", "Əlaqə"]
        }
    }
}


</script>

<style scoped>
header {
    width: 100%;
    height: 100px;
    position: sticky;
    top: 0;
    z-index: 1000;
}

nav {
    padding: 0px 10px;
    width: 1140px;
    min-width: 1140px;
    height: 100px;
    position: relative;
}

nav ul {
    gap: 20px;
    padding: 10px;
}

nav ul li {
    cursor: pointer;
}

nav ul:first-of-type li a:hover {
    text-decoration-line: underline;
    text-decoration-color: var(--primary-color);
    text-decoration-thickness: 2px;
}

.logo {
    width: 220px;
    height: 86px;
}

.menu-search {
    position: relative;
}

.menu-search-input {
    margin-top: 8px;
    padding: 8px;
    width: 250px;
    position: absolute;
    right: 0;
    z-index: 1;
}

.menu-search-input:focus {
    border-color: var(--primary-color);
}

.menu-language {
    position: relative;
}

.menu-language-dropdown {
    margin-top: 8px;
    position: absolute;
    left: 4px;
    transform: translateX(-20px);
    z-index: 1;
}

.menu-language-dropdown-item {
    padding: 10px 12px;
    cursor: pointer;
    transition: 200ms ease-in;
}

.menu-language-dropdown-item:hover {
    background-color: var(--light-color);
    color: var(--white-color);
    transition: 200ms ease-in;
}

.menu-language-dropdown-item + .menu-language-dropdown-item {
    border-top: 1px solid var(--light-color);
}

.menu-account {
    position: relative;
}

.menu-account-dropdown {
    margin-top: 16px;
    width: 150px;
    position: absolute;
    top: 100%;
    right: 0;
    z-index: 1;
}

.menu-account-dropdown-item {
    padding: 12px;
    cursor: pointer;
    transition: 300ms ease-in;
}

.menu-account-dropdown-item:hover {
    background-color: var(--light-color);
    color: var(--white-color);
    transition: 300ms ease-in;
}

.menu-account-dropdown-item + .menu-account-dropdown-item {
    border-top: 1px solid var(--primary-color);
}


</style>
