<template>
    <div class="text-headingsColor pt-6">
        <h2
            class="font-notoSans text-headingsColor text-twentyFour leading-thirtySix md:text-thirtyTwo md:leading-rightHeadingsDt rightSecHeading font-bold font-parrotGreen">
            {{ $t(title) }}
        </h2>
    </div>
</template>

<script>
export default {
    name: "SubHeading",
    props: ['title']
}
</script>