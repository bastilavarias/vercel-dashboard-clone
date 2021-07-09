<template>
    <div class="rounded-lg shadow bg-white divide-y">
        <div class="py-5 px-5 space-y-5">
            <div class="flex justify-between items-start">
                <h3 class="text-2xl font-semibold">next-nested-routing</h3>
                <a
                    href="#"
                    class="
                        border
                        rounded-md
                        border-gray-200
                        text-sm
                        leading-5
                        text-gray-600
                        px-4
                        py-1
                        hover:border-black
                        transition
                        duration-150
                    "
                >
                    Visit
                </a>
            </div>
            <div class="space-y-2">
                <div class="space-x-2">
                    <a href="#" class="inline-flex items-center space-x-2">
                        <span
                            class="
                                w-2.5
                                h-2.5
                                rounded-full
                                bg-green-400
                                inline-block
                                mt-0.5
                            "
                        ></span>
                        <span class="text-sm font-semibold lead-5"
                            >shamelesscomfort.com</span
                        >
                    </a>
                    <span
                        class="
                            inline-flex
                            items-center
                            border border-gray-200
                            px-1
                            py-0.5
                            text-xs
                            rounded-lg
                            font-medium
                            bg-gray-50
                            font-medium
                        "
                        >Production</span
                    >
                    <span class="text-gray-500">204d</span>
                </div>
                <div class="space-x-2">
                    <a href="#" class="inline-flex items-center space-x-2">
                        <span
                            class="
                                w-2.5
                                h-2.5
                                rounded-full
                                bg-green-400
                                inline-block
                                mt-0.5
                            "
                        ></span>
                        <span class="text-sm font-semibold lead-5"
                            >next-nested-routing-5ipzp1m88.now.sh</span
                        >
                    </a>
                    <span
                        class="
                            inline-flex
                            items-center
                            border border-gray-200
                            px-1
                            py-0.5
                            text-xs
                            rounded-lg
                            font-medium
                            bg-gray-50
                            font-medium
                        "
                        >Latest</span
                    >
                    <span class="text-gray-500">46D</span>
                </div>
            </div>
        </div>
        <div class="py-3 px-5">
            <span
                class="
                    flex
                    items-center
                    space-x-1
                    text-xs
                    leading-5
                    text-black
                    font-semibold
                "
            >
                <GithubLogo />
                <span class=""> bastilavarias/next-nested-routing </span>
            </span>
        </div>
    </div>
</template>

<script>
import GithubLogo from '@/components/logo/Github';

export default {
    name: 'rojectCard',

    components: { GithubLogo },
};
</script>
