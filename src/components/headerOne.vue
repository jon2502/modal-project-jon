<template>
    <div id="gridHeader">
        <h1 @click="ToggleBtn('a')"> {{ title }}</h1>
    <ul id="menu">
        <ul>
            <button @click="ToggleBtn('b')" >Brandr</button>
        </ul>
        <ul>
            <button @click="ToggleBtn('c')">Gethlire</button>
        </ul>
        <ul>
            <button @click="ToggleBtn('d')">Scathach</button>
        </ul>
        <ul>
            <button @click="ToggleBtn('e')">name pending</button>
        </ul>
    </ul>
    </div>
</template>

<script>
export default {
    props: [
        'title',
        
    ],
    methods: {
    ToggleBtn(id){
      this.$emit('toggle', id)
    }
  }
}
</script>

<style>
#gridHeader{
    display: grid;
    padding-left: 4vw;
    grid-template-columns: 20% 80%;
    background-color: rosybrown;
}
#menu{
    display: grid;
    grid-template-columns: repeat(4,10vw);
    justify-content: center;
    align-content: center;
}
</style>