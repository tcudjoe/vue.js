<template>
    <section>
        <div class="content container diagonal-box">
            <h1 :style="{ color: color}"> {{ h1Text }}</h1>
        </div>
    </section>
</template>

<script>
    export default {
        name: 'Header',
        props: {
            color: String,
            h1Text: String,
        }
    }
</script>

<style>
    

</style>