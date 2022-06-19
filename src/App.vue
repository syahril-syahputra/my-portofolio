<template>
    <div>
        <div class="bg"></div>
<div class="bg bg2"></div>
<div class="bg bg3"></div>
        <div
            class="relative h-screen flex flex-col mx-5 space-y-10 justify-center items-center"
        >
            <img
                src="https://avatars.githubusercontent.com/u/99789285?v=4"
                class="border border-gray-500 rounded-full shadow-2xl"
            />
            <div class="flex flex-col text-center">
                <label class="font-bold text-2xl text-slate-700">
                    Hi.. i'm Syahril
                </label>
                <label class="font-bold text-4xl text-slate-500">
                    I'm a Full Stack Developer
                </label>
            </div>
            <div class="flex flex-col text-center font-bold text-red-600">
                <label class="font-bold text-lg"
                    >Sorry This Site Is Under Maintenance</label
                >
                <label class="text-base">Please Come Back Later!</label>
            </div>
        </div>
    </div>
</template>
<script lang="ts">
export default{}
</script>
<style>
html {
    height: 100%;
}

body {
    margin: 0;
}

.bg {
    animation: slide 3s ease-in-out infinite alternate;
    background-image: linear-gradient(-60deg, #f8c6a5 50%, rgb(148, 211, 253) 50%);
    bottom: 0;
    left: -50%;
    opacity: 0.5;
    position: fixed;
    right: -50%;
    top: 0;
    z-index: -1;
}

.bg2 {
    animation-direction: alternate-reverse;
    animation-duration: 4s;
}

.bg3 {
    animation-duration: 5s;
}

.content {
    background-color: rgba(255, 255, 255, 0.8);
    border-radius: 0.25em;
    box-shadow: 0 0 0.25em rgba(0, 0, 0, 0.25);
    box-sizing: border-box;
    left: 50%;
    padding: 10vmin;
    position: fixed;
    text-align: center;
    top: 50%;
    transform: translate(-50%, -50%);
}

h1 {
    font-family: monospace;
}

@keyframes slide {
    0% {
        transform: translateX(-25%);
    }
    100% {
        transform: translateX(25%);
    }
}
</style>
