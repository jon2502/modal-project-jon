<template>
    <h1> {{ title }}</h1>
    <ul>
        <ul>
            <a href="test1">test1</a>
        </ul>
        <ul>
            <a href="test2">test2</a>
        </ul>
        <ul>
            <a href="test3">test3</a>
        </ul>
        <ul>
            <a href="test4">test3</a>
        </ul>
    </ul>

</template>

<script>
export default {
    props: [
        'title',
    ]
}
</script>

<style>

</style>