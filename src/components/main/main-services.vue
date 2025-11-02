<template>
    <section class="calltoaction-section">
        <div
            class="calltoaction-section-container display-flex-row-space-between-center border-radius-8px background-color-white">
            <div class="calltoaction-section-item display-flex-column-flex-start-center">
                <div class="text-bold-20px text-color-primary">Xoşbəxt Müştəri</div>
                <div class="calltoaction-section-item-numbers display-flex-row-space-between-center">
                    <div class="icon background-color-primary" style="
                                    mask-image: url('/src/assets/icons/icon-clients.svg');
                                    width: 50px;
                                    height: 50px;
                                "></div>
                    <div>
                        <h2 class="text-color-primary">250</h2>
                    </div>
                </div>
            </div>
            <div class="calltoaction-section-item display-flex-column-flex-start-center">
                <div class="text-bold-20px text-color-primary">Aktiv Xidmət</div>
                <div class="calltoaction-section-item-numbers display-flex-row-space-between-center">
                    <div class="icon background-color-primary" style="
                                    mask-image: url('src/assets/icons/icon-services.svg');
                                    width: 50px;
                                    height: 50px;
                                "></div>
                    <div>
                        <h2 class="text-color-primary">326</h2>
                    </div>
                </div>
            </div>
            <div class="calltoaction-section-item display-flex-column-flex-start-center">
                <div class="text-bold-20px text-color-primary">Təcrübəmiz(il)</div>
                <div class="calltoaction-section-item-numbers display-flex-row-space-between-center">
                    <div class="icon background-color-primary"
                        style="mask-image: url('src/assets/icons/icon-time.svg'); width: 50px; height: 50px"></div>
                    <div>
                        <h2 class="text-color-primary">12</h2>
                    </div>
                </div>
            </div>
            <div class="calltoaction-section-item display-flex-column-flex-start-center">
                <div class="text-bold-20px text-color-primary">Mütəxəssislərimiz</div>
                <div class="calltoaction-section-item-numbers display-flex-row-space-between-center">
                    <div class="icon background-color-primary" style="
                                    mask-image: url('src/assets/icons/icon-specialist.svg');
                                    width: 50px;
                                    height: 50px;
                                "></div>
                    <div>
                        <h2 class="text-color-primary">8</h2>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <section class="services-section display-flex-column-flex-start-center background"
        style="background-image: url('src/assets/images/background-services.png')">
        <h3 class="text-color-primary">XİDMƏTLƏRİMİZ</h3>
        <div class="services-section-container display-flex-row-space-around-center">
            <div class="services-section-items border-2px-primary border-radius-8px display-flex-row-center-center">
                <img src="@/assets/images/cloud-server.png" alt="" />
                <div class="services-section-items-image background-color-primary"></div>
                <div
                    class="services-section-items-title border-2px-primary background-color-white border-radius-8px text-regular-14px text-color-primary display-flex-row-center-center">
                    Bulud Serverlər
                </div>
            </div>
            <div class="services-section-items border-2px-primary border-radius-8px display-flex-row-center-center">
                <img src="@/assets/images/mail.png" alt="" />
                <div class="services-section-items-image background-color-primary"></div>
                <div
                    class="services-section-items-title border-2px-primary background-color-white border-radius-8px text-regular-14px text-color-primary display-flex-row-center-center">
                    Korporativ Mail
                </div>
            </div>
            <div class="services-section-items border-2px-primary border-radius-8px display-flex-row-center-center">
                <img src="@/assets/images/ip-telephony.png" alt="" />
                <div class="services-section-items-image background-color-primary"></div>
                <div
                    class="services-section-items-title border-2px-primary background-color-white border-radius-8px text-regular-14px text-color-primary display-flex-row-center-center">
                    IP Telefoniya
                </div>
            </div>
            <div class="services-section-items border-2px-primary border-radius-8px display-flex-row-center-center">
                <img src="@/assets/images/webhosting.png" alt="" />
                <div class="services-section-items-image background-color-primary"></div>
                <div
                    class="services-section-items-title border-2px-primary background-color-white border-radius-8px text-regular-14px text-color-primary display-flex-row-center-center">
                    Veb Hostinq
                </div>
            </div>
            <div class="services-section-items border-2px-primary border-radius-8px display-flex-row-center-center">
                <img src="@/assets/images/activedirectory.png" alt="" />
                <div class="services-section-items-image background-color-primary"></div>
                <div
                    class="services-section-items-title border-2px-primary background-color-white border-radius-8px text-regular-14px text-color-primary display-flex-row-center-center">
                    Active Directory
                </div>
            </div>
            <div class="services-section-items border-2px-primary border-radius-8px display-flex-row-center-center">
                <img src="@/assets/images/itoutsourcing.png" alt="" />
                <div class="services-section-items-image background-color-primary"></div>
                <div
                    class="services-section-items-title border-2px-primary background-color-white border-radius-8px text-regular-14px text-color-primary display-flex-row-center-center">
                    İT Autsorsinq
                </div>
            </div>
        </div>
    </section>


</template>

<script></script>


<style scoped>
.calltoaction-section {
    position: relative;
    z-index: 1;
}

.calltoaction-section-container {
    width: 1000px;
    height: 160px;
    padding: 0px 40px;
    box-shadow: 4px 4px 8px 4px rgba(0, 0, 0, 0.25);
    position: absolute;
    top: -80px;
    left: 50%;
    transform: translateX(-50%);
}

.calltoaction-section-item {
    gap: 4px;
}

.calltoaction-section-item-numbers {
    gap: 12px;
}

/* services section */

.services-section {
    width: 100%;
    height: 856px;
    position: relative;
}

.services-section h3 {
    margin-top: 120px;
}

.services-section-container {
    margin-top: 40px;
    width: 1120px;
    row-gap: 75px;
    flex-wrap: wrap;
}

.services-section-items {
    width: 340px;
    height: 250px;
    position: relative;
    /* flex: 1 1 33.333%; */
}

.services-section-items-image {
    background-color: var(--dark-color);
    cursor: pointer;
    width: 100%;
    height: 100%;
    position: absolute;
    top: 0;
    left: 0;
    opacity: 0%;
    transition: 500ms ease-in;
}

.services-section-items-title {
    cursor: pointer;
}

.services-section-items:hover .services-section-items-image {
    opacity: 60%;
    transition: 500ms ease-in;
}

.services-section-items-title {
    width: 240px;
    height: 40px;
    position: absolute;
    top: -20px;
    left: 50%;
    transform: translateX(-50%);
}
</style>