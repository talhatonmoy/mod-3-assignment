<script setup>


const button = {
    textPurchase: "Purchase Now",
    url: "https://rebrand.ly/appland-ud"

}


</script>

<template>
    <a :href="button.url" rel="nofollow" class="main-btn">{{ button.textPurchase }}</a>
</template>

<style scoped></style>