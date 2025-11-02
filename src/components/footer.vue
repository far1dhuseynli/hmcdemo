<template>
    <footer class="background-color-primary display-flex-column-flex-start-center">
            <div class="footer-wrapper display-flex-row-space-between-center">
                <ul class="footer-wrapper-left">
                    <li class="text-color-white">
                        <a href="#" class="text-light-16px">Konfidensiallıq siyasəti</a>
                    </li>
                    <li class="text-color-white">
                        <a href="#" class="text-light-16px">Şərtlər və qaydalar</a>
                    </li>
                    <li class="text-color-white">
                        <a href="#" class="text-light-16px">Şikayət və təkliflər</a>
                    </li>
                    <li class="text-color-white">
                        <a href="#" class="text-light-16px">Mütəmadi verilən suallar</a>
                    </li>
                </ul>
                <div class="footer-wrapper-right display-flex-column-space-between-end">
                    <form action="#">
                        <label for="subscribe" class="text-color-white text-regular-20px">Bizə abunə olun:</label>
                        <div class="display-flex-row-space-between-center">
                            <input
                                type="text"
                                id="subscribe"
                                placeholder="Enter your mail..."
                                class="text-regular-16px text-color-primary border-radius-8px border-2px-primary" />
                            <button class="btn-white">Abunə olmaq</button>
                        </div>
                    </form>
                    <div class="text-color-white text-regular-16px">© 2024 HMC Company. Bütün hüquqlar qorunur.</div>
                </div>
            </div>
        </footer>
</template>

<script>
</script>


<style scoped>

.footer-wrapper {
    width: 1120px;
    height: 150px;
    margin-top: 10px;
}

.footer-wrapper input {
    width: 324px;
    height: 46px;
    padding: 0 16px;
    margin-right: 8px;
}

.footer-wrapper-left {
    margin: 0;
    height: 100%;
}

.footer-wrapper-right {
    height: 100%;
}


</style>