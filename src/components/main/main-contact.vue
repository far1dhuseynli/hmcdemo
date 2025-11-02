<template>

    <section class="contact-section display-flex-column-flex-start-center background"
        style="background-image: url(src/assets/images/background-contact.png)">
        <h3 class="text-color-primary">BİZİMLƏ ƏLAQƏ</h3>
        <div class="contact-section-container display-flex-row-space-between-center">
            <div class="contact-section-contact-wrapper display-flex-column-space-between-flex-start">
                <div class="contact-section-contact display-flex-column-space-between-flex-start">
                    <div class="contact-section-contact-item display-flex-row-center-center">
                        <div class="icon background-color-primary" style="
                                        mask-image: url('src/assets/icons/icon-map.svg');
                                        width: 50px;
                                        height: 50px;
                                    "></div>
                        <div class="display-flex-column-space-between-flex-start">
                            <div class="text-color-primary text-bold-20px">Ünvan:</div>
                            <div class="text-color-primary text-regular-20px">
                                <a href="https://maps.app.goo.gl/eKYGsKzrPDbzWFtp6" target="_blank">Baki, Azərbaycan</a>
                            </div>
                        </div>
                    </div>
                    <div class="contact-section-contact-item display-flex-row-center-center">
                        <div class="icon background-color-primary" style="
                                        mask-image: url('src/assets/icons/icon-mail.svg');
                                        width: 50px;
                                        height: 50px;
                                    "></div>
                        <div class="display-flex-column-space-between-flex-start">
                            <div class="text-color-primary text-bold-20px">Email:</div>
                            <div class="text-color-primary text-regular-20px">
                                <a href="cdn-cgi/l/email-protection.html#1d74737b725d75707e337c67"><span
                                        class="__cf_email__"
                                        data-cfemail="b6dfd8d0d9f6dedbd598d7cc">Info@hmc.az</span></a>
                            </div>
                        </div>
                    </div>
                    <div class="contact-section-contact-item display-flex-row-center-center">
                        <div class="icon background-color-primary" style="
                                        mask-image: url('src/assets/icons/icon-phone.svg');
                                        width: 50px;
                                        height: 50px;
                                    "></div>
                        <div class="display-flex-column-space-between-flex-start">
                            <div class="text-color-primary text-bold-20px">Telefon:</div>
                            <div class="text-color-primary text-regular-20px">
                                <a href="tel:+994123105511">+994 12 310 55 11</a>
                            </div>
                        </div>
                    </div>
                    <div class="contact-section-contact-item display-flex-row-center-center">
                        <div class="icon background-color-primary" style="
                                        mask-image: url('src/assets/icons/icon-mobile.svg');
                                        width: 50px;
                                        height: 50px;
                                    "></div>
                        <div class="display-flex-column-space-between-flex-start">
                            <div class="text-color-primary text-bold-20px">Mobil:</div>
                            <div class="text-color-primary text-regular-20px">
                                <a href="tel:+994774775511">+994 77 477 55 11</a>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="contact-section-contact-sosial">
                    <div class="text-bold-20px text-color-primary">Sosial şəbəkələrdə bizi izləyin</div>
                    <div class="contact-section-contact-sosial-items display-flex-row-space-between-center">
                        <a href="https://wa.me/994774775511" target="_blank">
                            <div class="icon btn-icon-primary" style="
                                            mask-image: url('src/assets/icons/icon-whatsapp.svg');
                                            width: 70px;
                                            height: 70px;
                                        "></div>
                        </a>
                        <a href="https://t.me/hmccompany" target="_blank">
                            <div class="icon btn-icon-primary" style="
                                            mask-image: url('src/assets/icons/icon-telegram.svg');
                                            width: 70px;
                                            height: 70px;
                                        "></div>
                        </a><a href="https://www.linkedin.com/company/hmccompany/" target="_blank">
                            <div class="icon btn-icon-primary" style="
                                            mask-image: url('src/assets/icons/icon-linkedin.svg');
                                            width: 70px;
                                            height: 70px;
                                        "></div>
                        </a>
                        <a href="https://www.facebook.com/hmccompany.az" target="_blank">
                            <div class="icon btn-icon-primary" style="
                                            mask-image: url('src/assets/icons/icon-facebook.svg');
                                            width: 70px;
                                            height: 70px;
                                        "></div>
                        </a>
                        <a href="https://www.instagram.com/hmccompany.az/" target="_blank">
                            <div class="icon btn-icon-primary" style="
                                            mask-image: url('src/assets/icons/icon-instagram.svg');
                                            width: 70px;
                                            height: 70px;
                                        "></div>
                        </a>
                        <a href="https://youtube.com/" target="_blank">
                            <div class="icon btn-icon-primary" style="
                                            mask-image: url('src/assets/icons/icon-youtube.svg');
                                            width: 70px;
                                            height: 70px;
                                        "></div>
                        </a>
                    </div>
                </div>
            </div>
            <div class="contact-section-form">
                <form action="#" class="border-2px-primary border-radius-8px display-flex-column-center-center">
                    <div>
                        <label for="name"
                            class="text-bold-20px text-color-primary background-color-white border-radius-8px">Ad və
                            Soyad</label>
                        <input type="text" name="name" id="name" maxlength="25"
                            class="text-regular-16px background-color-white text-color-primary border-radius-8px border-2px-primary" />
                    </div>
                    <div>
                        <label for="phone"
                            class="text-bold-20px text-color-primary background-color-white border-radius-8px">Əlaqə
                            nömrəsi</label>
                        <input type="tel" name="phone" id="phone" maxlength="25"
                            class="text-regular-16px background-color-white text-color-primary border-radius-8px border-2px-primary" />
                    </div>
                    <div>
                        <label for="email"
                            class="text-bold-20px text-color-primary background-color-white border-radius-8px">Email</label>
                        <input type="email" name="email" id="email" maxlength="25"
                            class="text-regular-16px background-color-white text-color-primary border-radius-8px border-2px-primary" />
                    </div>
                    <div>
                        <label for="mesaj"
                            class="text-bold-20px text-color-primary background-color-white border-radius-8px">Mesajınız</label>
                        <textarea name="mesaj" id="mesaj" maxlength="140"
                            class="text-regular-16px background-color-white text-color-primary border-radius-8px border-2px-primary"></textarea>
                    </div>
                    <button class="btn-primary">Göndər</button>
                </form>
            </div>
        </div>
    </section>

</template>

<script></script>


<style>
.contact-section {
    width: 100%;
    height: 700px;
}

.contact-section-container {
    margin-top: 40px;
    column-gap: 196px;
}

.contact-section-contact-wrapper {
    height: 484px;
}

.contact-section h3 {
    margin-top: 80px;
}

.contact-section-contact {
    gap: 10px;
}

.contact-section-contact-item {
    gap: 12px;
}

.contact-section-contact-sosial-items {
    gap: 20px;
    margin-top: 10px;
}

.contact-section-form form {
    gap: 20px;
    padding: 20px;
    padding-top: 40px;
    width: 400px;
    height: 480px;
    padding: 0;
    margin: 0;
}

.contact-section-form form div {
    position: relative;
}

.contact-section-form form div input {
    width: 360px;
    height: 50px;
    margin: 0;
    padding: 0 16px;
    box-sizing: border-box;
}

.contact-section-form form div textarea {
    width: 360px;
    height: 150px;
    resize: none;
    margin: 0;
    padding: 8px 16px;
    box-sizing: border-box;
}

.contact-section-form form div label {
    position: absolute;
    top: -15px;
    left: 15px;
    padding: 0 8px;
}
</style>