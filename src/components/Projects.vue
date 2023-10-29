<template>
    <h2 class="text-[46px] py-16">Experience And Portfolio</h2>
    <div class="flex flex-wrap justify-center">
        <div class="p-6" v-for="proj in 4" :key="proj">
            <Project />
        </div>
    </div>
</template>

<script>
import Project from "./ProjectCard.vue"
export default {
    name: "TheProjects",
    components: { Project },
    data() {
        return {

        }
    }
}
</script>