<template>
    <div>
        <p>{{ monstername }}</p>
    </div>
</template>

<script>
export default {
    name: "MonsterName",
    data() {
            return {
                monstername:"Tobi Kadatchi"
            }
        },
}
</script>

<style scoped>

p{
    margin: 0;
    color: white;
    font-weight: 700;
    letter-spacing: 8px;
    padding: 0;
    padding-right: 15px;
    padding-left: 15px;
    text-align: center;
    font-size: 30px;
    font-family:cursive;
    background-color: rgb(83, 83, 83);
    border-radius: 25px;

}

</style>