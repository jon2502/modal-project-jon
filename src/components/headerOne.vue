<template>
    <div id="gridHeader">
        <h1> {{ title }}</h1>
    <ul id="menu">
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
    </div>
</template>

<script>
export default {
    props: [
        'title',
    ]
}
</script>

<style>
#gridHeader{
    display: grid;
    grid-template-columns: 20vw 80vw;
    background-color: rosybrown;
}
#menu{
    display: grid;
    grid-template-columns: repeat(4,6rem);
}
</style>