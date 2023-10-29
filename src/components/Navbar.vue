<template>
    <div class="flex justify-between ">
        <h3 class="text-3xl">P.S. Protfolio</h3>
        <ul class="flex justify-around text-lg">
            <li class="px-8">Projects</li>
            <li class="px-8">Technologies</li>
            <li class="px-8">About me</li>
        </ul>
        <div class="flex">
            <a href="" target="_blank"><img src="../assets/Linkdin.png" alt="linkdin" height="27" width="27" class="mx-4" @click="goToLink('Linkdin')"></a>
            <a href="" target="_blank"><img src="../assets/Linkdin.png" alt="github" height="27" width="27" class="mx-4" @click="goToLink('Github')"></a>
        </div>
    </div>
</template>

<script>
    export default {
        name: "TheNavabr",
        data() {
            return {
                name: "pratik"
            }
        },
        methods: {
            // goToLink(platform) {
            //     switch (platform) {
            //         case Linkdin:
            //             Window.op
            //             break;
            //         case Github:
                
            //         default:
            //             break;
            //     }
            // }
        }
    }
</script>