<template>

<section class="hero-card">
    <HeroCardImage />
    <HeroCardIntro />
</section>

</template>

<script>
import HeroCardImage from '@/components/HeroCardImage.vue';
import HeroCardIntro from '@/components/HeroCardIntro.vue';

export default {
    components: {
        HeroCardIntro,
        HeroCardImage
    }
}

</script>

<style lang="scss" scoped>

    .hero-card {
        display: flex;
        justify-content: space-between;
        flex-direction: row;
    }

</style>