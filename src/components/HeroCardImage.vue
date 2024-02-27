<template>
    <div class="profile-image">
        <img src="@/assets/images/profile.jpg">
    </div>
</template>

<style lang="scss" scoped>

$size: 20rem;

.profile-image {
    border-radius: $size;
    overflow: hidden;
    width: $size;
    height: $size;
    margin: 0 5rem 0 0;
    img {
        width: $size;
    }
}

</style>