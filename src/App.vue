<template>
    <section>
        <header class="bg-white border-b-2 border-gray-200">
            <nav
                class="
                    max-w-5xl
                    mx-auto
                    px-6
                    py-4
                    flex
                    items-center
                    justify-between
                "
            >
                <div class="flex items-center space-x-3">
                    <VercelLogo class-name="h-6" />
                    <span>
                        <svg
                            viewBox="0 0 32 32"
                            stroke="currentColor"
                            class="text-gray-300 h-8 w-8"
                        >
                            <line x1="8" y1="28" x2="24" y2="4" />
                        </svg>
                    </span>
                    <span
                        class="
                            inline-flex
                            items-center
                            text-sm
                            leading-5
                            font-medium
                            space-x-2
                        "
                    >
                        <a href="#" class="inline-flex items-center space-x-2">
                            <span>
                                <Avatar />
                            </span>
                            <span>Sebastian Lavarias</span>
                        </a>
                        <button
                            type="button"
                            class="
                                inline-flex
                                items-center
                                border border-transparent
                                rounded-md
                                py-0.5
                                transition
                                duration-300
                                hover:border-gray-300 hover:bg-gray-50
                            "
                        >
                            <SelectorIcon class="h-5 w-5 text-gray-400" />
                        </button>
                    </span>
                </div>
                <div class="flex items-center space-x-5">
                    <div class="flex items-center space-x-4">
                        <button
                            type="button"
                            class="
                                border
                                rounded-md
                                border-gray-200
                                text-sm
                                leading-5
                                text-gray-600
                                px-3
                                py-1.5
                                hover:border-black
                                transition
                                duration-150
                            "
                        >
                            Feedback
                        </button>
                        <a
                            href="#"
                            class="
                                inline-block
                                text-sm
                                leading-5
                                text-gray-600
                                hover:text-black
                            "
                            >Blog</a
                        >
                        <a
                            href="#"
                            class="
                                inline-block
                                text-sm
                                leading-5
                                text-gray-600
                                hover:text-black
                            "
                            >Support</a
                        >
                        <a
                            href="#"
                            class="
                                inline-block
                                text-sm
                                leading-5
                                text-gray-600
                                hover:text-black
                            "
                            >Docs</a
                        >
                    </div>
                    <button type="button">
                        <DotsHorizontalIcon class="w-5 h-5 text-gray-400" />
                    </button>
                    <span class="inline-flex items-center">
                        <button type="button">
                            <Avatar />
                        </button>
                    </span>
                </div>
            </nav>
            <div class="max-w-5xl mx-auto px-6">
                <nav
                    class="-mb-px flex text-sm items-center leading-5 space-x-5"
                >
                    <a
                        href="#"
                        class="lead-5 py-3 px-0.5 border-b-2 border-black"
                        >Overview</a
                    >
                    <a
                        href="#"
                        class="
                            lead-5
                            py-3
                            px-0.5
                            text-gray-500
                            hover:text-black
                            transition
                            ease-in-out
                            duration-200
                        "
                        >Projects</a
                    >
                    <a
                        href="#"
                        class="
                            lead-5
                            py-3
                            px-0.5
                            text-gray-500
                            hover:text-black
                            transition
                            ease-in-out
                            duration-200
                        "
                        >Integrations</a
                    >
                    <a
                        href="#"
                        class="
                            lead-5
                            py-3
                            px-0.5
                            text-gray-500
                            hover:text-black
                            transition
                            ease-in-out
                            duration-200
                        "
                        >Activity</a
                    >
                    <a
                        href="#"
                        class="
                            lead-5
                            py-3
                            px-0.5
                            text-gray-500
                            hover:text-black
                            transition
                            ease-in-out
                            duration-200
                        "
                        >Domains</a
                    >
                    <a
                        href="#"
                        class="
                            lead-5
                            py-3
                            px-0.5
                            text-gray-500
                            hover:text-black
                            transition
                            ease-in-out
                            duration-200
                        "
                        >Usage</a
                    >
                    <a
                        href="#"
                        class="
                            lead-5
                            py-3
                            px-0.5
                            text-gray-500
                            hover:text-black
                            transition
                            ease-in-out
                            duration-200
                        "
                        >Settings</a
                    >
                </nav>
            </div>
        </header>
        <div class="flex justify-between max-w-5xl mx-auto px-6 pt-14 pb-28">
            <div class="flex space-x-8">
                <div>
                    <img
                        src="https://pbs.twimg.com/profile_images/1409916834489409544/_Kfi_e8N_400x400.jpg"
                        alt="Avatar"
                        class="w-24 h-24 rounded-full"
                    />
                </div>
                <div class="flex flex-col justify-between">
                    <div class="flex items-center space-x-3">
                        <h1 class="text-4xl font-bold leading-10">
                            Sebastian Lavarias
                        </h1>
                        <span
                            class="
                                uppercase
                                border border-gray-200
                                px-2
                                py-0.5
                                text-xs
                                rounded-lg
                                font-medium
                                bg-gray-50
                                tracking-wide
                            "
                            >Hobby</span
                        >
                    </div>
                    <div>
                        <dl>
                            <dt
                                class="
                                    text-xs
                                    leading-5
                                    text-gray-500
                                    uppercase
                                    tracking-wide
                                    font-medium
                                "
                            >
                                Git Integration
                            </dt>
                            <dd
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
                                <span> bastilavarias </span>
                            </dd>
                        </dl>
                    </div>
                </div>
            </div>
            <div class="space-x-6">
                <a
                    href="#"
                    class="
                        inline-flex
                        border border-gray-200
                        font-medium
                        text-gray-500
                        rounded
                        px-6
                        bg-white
                        py-2
                        leading-5
                        text-sm
                        hover:border-black
                        ease-in-out
                        transition
                        duration-150
                    "
                    >Invite Team</a
                >
                <a
                    href="#"
                    class="
                        inline-flex
                        border border-transparent
                        font-medium
                        text-white
                        rounded
                        px-6
                        bg-black
                        py-2
                        leading-5
                        text-sm
                        hover:bg-white hover:border-black hover:text-black
                        ease-in-out
                        transition
                        duration-150
                    "
                    >Import Project</a
                >
            </div>
        </div>
    </section>
</template>

<script>
import { SelectorIcon, DotsHorizontalIcon } from '@heroicons/vue/solid';
import VercelLogo from '@/components/logo/Vercel';
import Avatar from '@/components/Avatar';
import GithubLogo from '@/components/logo/Github';

export default {
    name: 'App',

    components: {
        GithubLogo,
        Avatar,
        SelectorIcon,
        VercelLogo,
        DotsHorizontalIcon,
    },
};
</script>
