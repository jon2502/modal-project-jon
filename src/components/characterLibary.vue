<template>
    <section id="Libary">
        <div class="infoContainer">
            <div>
                <h2>Brandr Svensson</h2>
                <ul>
                    <li>Race: Half Elf</li>
                    <li>Culture: Thorwaler</li>
                    <li>Profession: Mercenary</li>
                    <li>Place of Birth: Waskir</li>
                </ul>
            </div>
            <img src="../assets/characterImg/Brander.png" alt="Brandr">
        </div>
        <div class="infoContainer">
            <div>
                <h2>Gethlire Keller</h2>
                <ul>
                    <li>Race: Half Elf</li>
                    <li>Culture: Garetian</li>
                    <li>former Profession: Mercenary</li>
                    <li>Place of Birth: info pending</li>
                </ul>
            </div>
            <img src="../assets/characterImg/Gethlire_Keller.png" alt="Gethlire Keller">
        </div>
        <div class="infoContainer">
            <div>
                <h2>Scathach summers</h2>
                <ul>
                    <li>Race: Human</li>
                    <li>Culture: Garetian</li>
                    <li>Profession: striker</li>
                    <li>Place of Birth: info pending</li>
                </ul>
            </div>
            <img src="../assets/characterImg/Scathach_summers.png" alt="Brandr">
        </div>
        <div class="infoContainer">
            <div>
                <h2>name pending</h2>
            <ul>
                <li>Race: tiefling</li>
                <li>Culture: info pending</li>
                <li>Profession: rogue</li>
                <li>Place of Birth: info pending</li>
            </ul>
            </div>
            <img src="../assets/characterImg/character.png" alt="Brandr">
        </div>
    </section>
</template>

<script>

</script>

<style>
    img{
        width: 50%;
    }
    #Libary{
        display: grid;
        grid-template-columns: repeat(2, 50%);
        row-gap: 5%;
    }
    .infoContainer{
        display: grid;
        grid-template-columns: repeat(2, 50%);
    }
</style>