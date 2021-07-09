<template>
    <div class="flex justify-between items-center py-3">
        <div class="flex items-center space-x-4">
            <Avatar />
            <span class="text-sm text-gray-600">
                <span class="text-black">You</span>
                logged in via GitHub
            </span>
        </div>
        <span class="text-gray-500 text-sm">26D</span>
    </div>
</template>

<script>
import Avatar from '@/components/Avatar';
export default {
    name: 'ActivityCard',
    components: { Avatar },
};
</script>
