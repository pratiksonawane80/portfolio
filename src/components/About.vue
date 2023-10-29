<template>
    <h2 class="text-[46px] font-semibold mt-16 mb-10">
        About Me
    </h2>
    <div>
        <div class="flex justify-between items-start text-3xl mt-10 font-semibold">
            <h3>2021</h3>
            <h3>2022</h3>
            <h3>2022</h3>
            <h3>2023</h3>
        </div>
        <!-- <div class="flex justify-between w-auto h-1 bg-white my-8">
            <div class="w-6 h-6 bg-gradient-to-r from-[#945DD6] via-[#6978D1] to-[#13ADC7] rounded-full"></div>
            <div class="w-6 h-6 bg-gradient-to-r from-[#945DD6] via-[#6978D1] to-[#13ADC7] rounded-full"></div>
            <div class="w-6 h-6 bg-gradient-to-r from-[#945DD6] via-[#6978D1] to-[#13ADC7] rounded-full"></div>
            <div class="w-6 h-6 bg-gradient-to-r from-[#945DD6] via-[#6978D1] to-[#13ADC7] rounded-full"></div>
        </div> -->
        <div class="">
            <!-- <div v-for="data in 4" :key="data" class="p-8">
                <div class="flex">
                    <div class=" h-1 bg-white my-8 w-96"></div>
                    <div class="w-6 h-6 bg-gradient-to-r from-[#945DD6] via-[#6978D1] to-[#13ADC7] rounded-full"></div>
                </div>
                <div>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Assumenda ex voluptas, perspiciatis ut
                    maiores
                    debitis itaque doloribus omnis aperiam unde consequuntur nisi quisquam. Accusamus quod modi qui
                    ullam
                    rerum
                    tempore tenetur, molestiae perferendis laborum placeat reprehenderit, non quisquam officia pariatur
                    corrupti
                    expedita adipisci repellendus illo.
                </div>
            </div> -->
            <!-- <div></div> -->
            <div class="flex flex-wrap">

                <div v-for="data in 4" :key="data" class="p-8">
                    <div class="flex w-auto my-8">
                        <div class="w-6 h-6 bg-gradient-to-r from-[#945DD6] via-[#6978D1] to-[#13ADC7] rounded-full"></div>
                        <div class="mt-3 h-1 bg-white w-52"></div>
                    </div>
                    <div class="w-60">
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Assumenda ex voluptas, perspiciatis ut
                        maiores
                        debitis itaque doloribus omnis aperiam unde consequuntur nisi quisquam. Accusamus quod modi qui
                        ullam
                        rerum
                        tempore tenetur, molestiae perferendis laborum placeat reprehenderit, non quisquam officia pariatur
                        corrupti
                        expedita adipisci repellendus illo.
                    </div>
                </div>
            </div>
        </div>

    </div>
</template>

<script>
export default {
    name: "AboutMe"
}
</script>
