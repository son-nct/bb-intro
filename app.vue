<script>
useHead({
  title: 'BURNING BROS 🔥',
  link: [
    { rel: 'icon', type: 'image/png', href: 'https://cdn.prod.website-files.com/6673cae5d9f6bd50157e1c79/6684ec10ed5e6888baf5d8f4_light%20mode%20favicon-256x256.svg' },
  ]
});
</script>

<template>
 <section>
        <video src="/public/fire.mp4" autoplay muted loop></video>
        <h1>
            <span>B</span>
            <span>U</span>
            <span>R</span>
            <span>N</span>
            <span>I</span>
            <span>N</span>
            <span>G &nbsp;</span>

            <span>B</span>
            <span>R</span>
            <span>O</span>
            <span>S</span>
        </h1>
    </section>
</template>

<style>
body {
    margin: 0;
    padding: 0
}

section {
    height: 100vh;
    background: #000;
}

video {
    object-fit: cover;
    width: 100%;
}

h1 {
    margin: 0;
    padding: 0;
    position: absolute;
    top: 50%;
    transform: translateY(-50%);
    width: 100%;
    text-align: center;
    color: #fff;
    font-size: 7em;
    font-family: arial black;
}

h1 span {
    display: inline-block;
    animation: animate 1s linear forwards;
}

@keyframes animate {
    0% {
        opacity: 0;
        transform: rotateY(90deg);
        filter: blur(10px);
    }

    100% {
        opacity: 1;
        transform: rotateY(0deg);
         filter: blur(0);
    }
}

h1 span:nth-child(1) {
    opacity: 0;
    animation-delay: 0.5s;
}

h1 span:nth-child(2) {
    opacity: 0;
    animation-delay: 0.75s;
}

h1 span:nth-child(3) {
    opacity: 0;
    animation-delay: 1s;
}

h1 span:nth-child(4) {
    opacity: 0;
    animation-delay: 1.25s;
}

h1 span:nth-child(5) {
    opacity: 0;
    animation-delay: 1.5s;
}

h1 span:nth-child(6) {
    opacity: 0;
    animation-delay: 1.75s;
}

h1 span:nth-child(7) {
    opacity: 0;
    animation-delay: 2s;
}

h1 span:nth-child(8) {
    opacity: 0;
    animation-delay: 2.25s;
}

h1 span:nth-child(9) {
    opacity: 0;
    animation-delay: 2.5s;
}

h1 span:nth-child(10) {
    opacity: 0;
    animation-delay: 2.75s;
}

h1 span:nth-child(11) {
    opacity: 0;
    animation-delay: 3s;
}
</style>