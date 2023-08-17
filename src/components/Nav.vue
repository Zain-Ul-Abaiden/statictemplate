<template>
    <header class="relative z-50 flex-none pt-2 m-8">
        <div class="mx-auto max-w-7xl px-8 flex flex-wrap-item-center justify-between">
            <div class="flex">
                <svg aria-hidden="true" viewBox="0 0 183 48" class="h-11 w-auto text-slate-900">
                    <path fill="#3B82F6" fill-rule="evenodd"
                        d="M1.172 21.172a4 4 0 000 5.656l20 20a4 4 0 105.656-5.656l-20-20a4 4 0 00-5.656 0z"
                        clip-rule="evenodd"></path>
                    <path fill="#93C5FD" fill-rule="evenodd"
                        d="M26.828 6.828a4 4 0 10-5.656-5.656l-19 19A3.987 3.987 0 015 19a3.98 3.98 0 012.827 1.172L10.657 23 26.828 6.828z"
                        clip-rule="evenodd"></path>
                </svg>
                <h class="text-2xl font-bold">DeceptiConf</h>
            </div>
            <div class="flex flex-auto border-blue-600/10 py-4 font-mono text-sm text-blue-600">
                <div class="mx-auto flex items-center gap-4 px-4">
                    <p>
                        04-06 of April, 2022
                    </p>
                    <svg viewBox="0 0 6 6" class="h-1.5 w-1.5 overflow-visible fill-current stroke-current">
                        <path d="M3 0L6 3L3 6L0 3Z" stroke-width="2" stroke-linejoin="round"></path>
                    </svg>
                    <p>Los Angeles, CA</p>
                </div>
                <div>
                    <a class="inline-flex justify-center rounded-2xl bg-blue-600 p-4 text-base font-semibold text-white hover:bg-blue-500 focus:outline-none focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-blue-500 active:text-white/70"
                        href="#">Get your tickets</a>
                </div>
            </div>
        </div>
    </header>
</template>
<script>
export default {
    name: 'Navbar',
};
</script>
