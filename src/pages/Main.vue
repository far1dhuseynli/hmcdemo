<template>
    <main>
        <main-carousel></main-carousel>
        <main-about></main-about>
        <main-services></main-services>
        <main-mission></main-mission>
        <main-contact></main-contact>
    </main>
</template>


<script>
import Carousel from "../components/main/main-carousel.vue"
import About from "../components/main/main-about.vue"
import Contact from "../components/main/main-contact.vue"
import Mission from "../components/main/main-mission.vue"
import Services from "../components/main/main-services.vue"

export default {
    components: {
        'main-carousel': Carousel,
        'main-about': About,
        'main-contact': Contact,
        'main-mission': Mission,
        'main-services': Services,
    }

}

</script>


<style scoped></style>