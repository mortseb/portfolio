<script setup></script>

<template>
    <footer class="bg-white rounded-lg shadow m-4 dark:bg-gray-800 absolute inset-x-0 bottom-0 h-16">
        <div class="w-full mx-auto max-w-screen-xl p-4 md:flex md:items-center md:justify-between">
            <span class="text-sm text-gray-500 sm:text-center dark:text-gray-400">© 2023 <a href="https://mortseb.com/"
                    class="hover:underline">Sébastien Mortiers</a>. All Rights Reserved.
            </span>
            <ul class="flex flex-wrap items-center mt-3 text-sm font-medium text-gray-500 dark:text-gray-400 sm:mt-0">
                <li>
                    <RouterLink to="/" class="hover:underline me-4 md:me-6">Accueil</RouterLink>
                </li>
                <li>
                    <RouterLink to="about/" class="hover:underline me-4 md:me-6">A Propos</RouterLink>
                </li>

            </ul>
        </div>
    </footer>
</template>
