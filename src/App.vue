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
                    <span class="hidden sm:block">
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
                            hidden
                            sm:block
                        "
                    >
                        <a href="#" class="inline-flex items-center space-x-2">
                            <span>
                                <Avatar />
                            </span>
                            <span class="hidden md:block"
                                >Sebastian Lavarias</span
                            >
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
                    <div class="flex items-center space-x-4 hidden sm:block">
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
                    <button type="button" class="hidden sm:block">
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
                    class="
                        -mb-px
                        flex
                        text-sm
                        items-center
                        leading-5
                        space-x-5
                        overflow-scroll
                    "
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
        <div class="bg-white border-b border-gray-200">
            <div
                class="flex justify-between max-w-5xl mx-auto px-6 pt-14 pb-28"
            >
                <div class="sm:flex space-x-0 sm:space-x-8">
                    <div class="hidden sm:block">
                        <img
                            src="https://pbs.twimg.com/profile_images/1409916834489409544/_Kfi_e8N_400x400.jpg"
                            alt="Avatar"
                            class="w-24 h-24 rounded-full"
                        />
                    </div>
                    <div
                        class="
                            flex flex-col
                            justify-between
                            space-y-5
                            lg:space-y-0
                        "
                    >
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
                        <div
                            class="
                                flex flex-col
                                space-y-3
                                sm:block sm:space-y-0 sm:space-x-5
                                lg:hidden
                            "
                        >
                            <a
                                href="#"
                                class="
                                    inline-flex
                                    justify-center
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
                                    justify-center
                                    border border-transparent
                                    font-medium
                                    text-white
                                    rounded
                                    px-6
                                    bg-black
                                    py-2
                                    leading-5
                                    text-sm
                                    hover:bg-white
                                    hover:border-black
                                    hover:text-black
                                    ease-in-out
                                    transition
                                    duration-150
                                "
                                >Import Project</a
                            >
                        </div>
                    </div>
                </div>
                <div class="space-x-6 hidden lg:block">
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
        </div>
        <div class="-mt-9">
            <main
                class="
                    max-w-5xl
                    mx-auto
                    px-6
                    grid grid-cols-12
                    pb-10
                    gap-y-20
                    lg:gap-y-0 lg:gap-20
                "
            >
                <div class="col-span-12 lg:col-span-7">
                    <h2 class="sr-only">Recent Projects</h2>
                    <ul class="space-y-10 mb-12">
                        <li v-for="n in 4">
                            <ProjectCard :key="n"></ProjectCard>
                        </li>
                    </ul>
                    <div>
                        <a
                            href="#"
                            class="
                                text-sm text-blue-500
                                font-bold
                                hover:underline
                            "
                            >View All Projects</a
                        >
                    </div>
                </div>
                <div class="col-span-12 lg:col-span-5 pt-1 space-y-12">
                    <h2 class="text-sm font-bold">Recent Activity</h2>
                    <ul
                        class="
                            border-b border-gray-200
                            divide-y divide-gray-200
                            mb-12
                        "
                    >
                        <li v-for="n in 18">
                            <ActivityCard :key="n" />
                        </li>
                    </ul>
                    <div>
                        <a
                            href="#"
                            class="
                                text-sm text-blue-500
                                font-bold
                                hover:underline
                            "
                            >View All Activities</a
                        >
                    </div>
                </div>
            </main>
        </div>
    </section>
</template>

<script>
import { SelectorIcon, DotsHorizontalIcon } from '@heroicons/vue/solid';
import VercelLogo from '@/components/logo/Vercel';
import Avatar from '@/components/Avatar';
import GithubLogo from '@/components/logo/Github';
import ProjectCard from '@/components/ProjectCard';
import ActivityCard from '@/components/ActivityCard';

export default {
    name: 'App',

    components: {
        ActivityCard,
        ProjectCard,
        GithubLogo,
        Avatar,
        SelectorIcon,
        VercelLogo,
        DotsHorizontalIcon,
    },
};
</script>
