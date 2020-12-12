<template>
    <div>
        <h1 class="font-normal text-3xl text-grey-darkest leading-none mb-4">
            Full Logo
        </h1>

        <div class="mb-10">
            <picture
                style="height: 382px"
                class="rounded-lg block shadow flex items-center justify-center mb-6"
            >
                <img src="/images/logo.svg" alt="logo">
            </picture>

            <div class="flex justify-between items-center">
                <p>Original logo on <strong>white</strong> background</p>

                <a
                    href="/images/logo.svg"
                    class="border border-grey px-8 py-2 rounded-full text-black font-bold text-xs">
                    logo.svg
                </a>
            </div>
        </div>

        <div>
            <picture
                style="height: 382px; background-color: darkblue"
                class="rounded-lg block shadow flex items-center justify-center mb-6"
            >
                <img src="/images/negative-logo.svg" alt="logo">
            </picture>

            <div class="flex justify-between items-center">
                <p>Negative logo on <strong>white</strong> background</p>

                <a
                    href="/images/negative-logo.svg"
                    class="border border-grey px-8 py-2 rounded-full text-black font-bold text-xs">
                    negative-logo.svg
                </a>
            </div>
        </div>
    </div>
</template>

<script>
    export default {

    }
</script>
