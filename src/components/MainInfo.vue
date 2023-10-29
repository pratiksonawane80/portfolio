<template>
    <div class="flex justify-between">
        <div class="text-[60px] font-semibold mr-10 w-3/5 my-40">
            <h1 class="bg-gradient-to-r from-[#945DD6] via-[#6978D1] to-[#13ADC7] inline-block text-transparent bg-clip-text">
                Hi, this is Pratik,
            </h1>
            <h3>Front End Developer</h3>
            <p class="text-lg font-medium font-lg text-[#929EB0] mt-6">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Odit, eos nostrum
                necessitatibus, ipsum velit incidunt consequatur magnam consequuntur harum maxime, vero ut consectetur
                asperiores? Atque!!
            </p>
            <a href="../assets/resume.pdf" download="">
            <button class="p-4 rounded-[60px] w-72 text-lg bg-gradient-to-r from-[#945DD6] via-[#6978D1] to-[#13ADC7]">
                Download CV
            </button>
            </a>
        </div>
        <div class="my-20 ">
            <div class="w-[532px] h-[532px] border rounded-full absolute bg-transparent right-[170px] mt-10 border-[#945DD6]"></div>
            <img src="../assets/display-pic.jpeg" alt="profile-pic" width="301"  height="301" class="rounded-full border border-[#945DD6] z-10 absolute right-40">
            <img src="../assets/blueCircle.svg" alt="cirlce" class="mt-40 ml-20">
        </div>
    </div>
</template>

<script>
export default {
    name: "MainInfo",
    data() {
        return {
            page: ""
        }
    }
}
</script>