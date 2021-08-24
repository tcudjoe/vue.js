<template>
    <section class="diagonal-box" id="diagonal-box">
        <div class="content">
            <h1 :style="{ color: color}"> {{ h1Text }}</h1>
            <p :style="{ color: color}">{{ textP }}</p>
        </div>
    </section>
</template>

<script>
    export default {
        name: 'Header',
        props: {
            textP: String,
            color: String,
            h1Text: String,
        }
    }
</script>

<style>
    

</style>