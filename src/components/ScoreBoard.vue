<template>

    <section class="score">
        Player <span>{{ this.winCount }}</span> X <span>{{ this.loseCount }}</span> Computer
    </section>

</template>

<script>
    export default{
        props: ['winCount', 'loseCount']
    }
</script>

<style lang="scss">

    section.score {
        border-bottom: 5px solid rgb(0, 0, 0);
        padding: 24px;
        font-size: 18px;
    }

    span {
    padding: 10px;
    font-weight: bold;
    border: 2px solid black;
    }

</style>