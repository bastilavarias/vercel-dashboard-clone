<template>
    <img
        :src="profileURL"
        alt="Avatar"
        class="h-7 w-7 rounded-full border border-gray-200"
    />
</template>

<script>
export default {
    name: 'Avatar',

    computed: {
        profileURL() {
            return 'https://pbs.twimg.com/profile_images/1409916834489409544/_Kfi_e8N_400x400.jpg';
        },
    },
};
</script>
