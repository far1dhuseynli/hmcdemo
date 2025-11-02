<template>
    <section
                class="main-section display-flex-row-center-center background"
                style="background-image: url(/src/assets/images/background-main.png)">
                <div class="main-section-container display-flex-row-space-between-center">
                    <div
                        class="icon btn-icon-primary"
                        style="mask-image: url('assets/icons/arrow-left.svg'); width: 60px; height: 60px"></div>
                    <div class="main-section-container-slide display-flex-row-space-between-center">
                        <div class="main-section-container-slide-intro display-flex-column-space-between-flex-start">
                            <h5 class="main-section-container-slide-intro-subtitle text-color-primary">
                                Yüksək performanslı
                            </h5>
                            <h2 class="main-section-container-slide-intro-title text-color-primary">
                                Bulud Serverlər!
                            </h2>
                            <button class="btn-primary">Daha ətraflı</button>
                        </div>
                        <div
                            class="main-section-container-slide-image background-color-white border-radius-8px border-2px-primary">
                            <img src="@/assets/images/cloud-server.png" alt="cloud server" />
                        </div>
                    </div>
                    <div class="main-section-container-slide display-flex-row-space-between-center display-none">
                        <div
                            class="main-section-container-slide-image background-color-white border-radius-8px border-2px-primary">
                            <img src="@/assets/images/cloud-server.png" alt="cloud server" />
                        </div>
                        <div class="main-section-container-slide-intro display-flex-column-space-between-flex-start">
                            <h5 class="main-section-container-slide-intro-subtitle text-color-primary">
                                Yüksək performanslı2
                            </h5>
                            <h2 class="main-section-container-slide-intro-title text-color-primary">
                                Bulud Serverlər2!
                            </h2>
                            <button class="btn-primary">Daha ətraflı</button>
                        </div>
                    </div>
                    <div
                        class="icon btn-icon-primary"
                        style="mask-image: url('assets/icons/arrow-right.svg'); width: 60px; height: 60px"></div>
                </div>
                <div class="main-section-scroll display-flex-row-center-center">
                    <div class="main-section-scroll-item border-radius-4px btn-icon-primary"></div>
                    <div class="main-section-scroll-active-item border-radius-8px btn-icon-primary"></div>
                    <div class="main-section-scroll-item border-radius-4px btn-icon-primary"></div>
                    <div class="main-section-scroll-item border-radius-4px btn-icon-primary"></div>
                    <div class="main-section-scroll-item border-radius-4px btn-icon-primary"></div>
                </div>
            </section>
</template>

<script>
export default {
  data() {
    return {
    }

  },

}
</script>


<style>
.main-section {
    width: 100%;
    height: 700px;
    position: relative;
}

.main-section-container {
    width: 1400px;
    min-width: 1140px;
    height: 700px;
}

.main-section-container-slide {
    padding: 0px;
    width: 980px;
}

.main-section-container-slide-intro {
    padding: 0px;
    height: 280px;
}

.main-section-container-slide-image {
    width: 376px;
    height: 352px;
}

.main-section-container-slide-intro-title {
    width: 500px;
    height: 132px;
}

.main-section-container-slide-intro-subtitle {
    width: 500px;
    height: 35px;
}

.main-section-scroll {
    position: absolute;
    bottom: 20px;
    gap: 20px;
}

.main-section-scroll-item {
    width: 40px;
    height: 8px;
}

.main-section-scroll-active-item {
    width: 46px;
    height: 12px;
}
</style>