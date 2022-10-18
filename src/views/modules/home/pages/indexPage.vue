<template>
    <div>
        <div>
            <div>
                <HeroSection/>
                <OurServices/>
                <AmazingFeatures/>
                <OurNews/>
                <AppFooter/>   
            </div>
        </div>
    </div>
</template>

<script>
import HeroSection from '../components/heroSection.vue';
import OurServices from '../components/ourServices.vue';
import AmazingFeatures from '../components/amazingFeatures.vue';
import OurNews from '../components/ourNews.vue';
import AppFooter from '../components/appFooter.vue';
export default {
    components: { HeroSection, OurServices, AmazingFeatures, OurNews, AppFooter }
}
</script>