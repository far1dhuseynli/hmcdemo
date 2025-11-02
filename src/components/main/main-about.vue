<template>
    <section
                class="aboutus-section display-flex-column-flex-start-center background"
                style="background-image: url(src/assets/images/background-aboutus.png)">
                <h3 class="text-color-white">HAQQIMIZDA</h3>
                <div class="aboutus-section-container display-flex-row-space-between-center">
                    <div class="aboutus-section-container-image">
                        <img src="@/assets/images/macbook.png" alt="" />
                    </div>
                    <div class="aboutus-section-container-intro display-flex-column-space-between-center">
                        <h4 class="aboutus-section-container-intro-title text-color-white">BİZ KİMİK?</h4>
                        <div class="aboutus-section-container-intro-text text-color-white">
                            “HMC Company” 2013-cü ildə fəaliyyətə başlamışdır. İstər kiçik ölçülü, istərsə də böyük
                            ölçülü şirkətlərə peşəkar səviyyədə İnformasiya Kommunikasiya Texnologiyaları (İKT)
                            xidmətləri göstəririk. Bu sahədə əsas fərqli cəhətimiz ən qabaqcıl texnoloji biliklərə və
                            təcrübəyə sahib aparıcı mütəxəssislərimizin olması və dünyanın ən qabaqcıl şirkətləri ilə
                            əməkdaşlıq etməyimizdir. Təhlükəsizlik və etibarlılığın ən yüksək tələblərinə cavab verən
                            Məlumat Mərkəzlərində bulud serverlər təklif edirik.
                        </div>
                        <button class="btn-white">Daha ətraflı</button>
                    </div>
                </div>
            </section>
</template>

<script></script>


<style scoped>
.aboutus-section {
    width: 100%;
    height: 700px;
    position: relative;
}

.aboutus-section h3 {
    margin-top: 80px;
    align-self: center;
}

.aboutus-section-container {
    margin: 60px 0 0 0;
    padding: 0;
    width: 1120px;
    height: 320px;
}

.aboutus-section-container-image {
    width: 534px;
    height: 320px;
}

.aboutus-section-container-intro {
    width: 550px;
    height: 320px;
}

.aboutus-section-container-intro-text {
    text-align: justify;
}
</style>