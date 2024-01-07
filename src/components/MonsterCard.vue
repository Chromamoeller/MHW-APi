<template>
    <div class="myCard">
        <div class="header">
            <MonsterName/>
        </div>
        <div class="pic"><MonsterPic/></div>
        <div class="content">sdf</div>
    </div>
</template>
<script>
import MonsterName from './MonsterName.vue';
import MonsterPic from './MonsterPic.vue';
export default {
    name: "MonsterCard",
    setup() {
        return {};
    },
    components: { MonsterName, MonsterPic }
}
</script>

<style scoped>

.myCard{
    min-width: 300px;
    min-height: 300px;
    background-color: rgba(65, 65, 65, 0.342);
    border-radius: 25px;
    margin: 25px;
    padding-left: 1.6rem;
    padding-right: 1.6rem;
    padding-top: 1rem;
    padding-bottom: 1rem;
}
.header{
    height: 50px;
    margin-bottom: 1rem;
}
.pic{
    height: 125px;
    background-color: brown;
}
.content{
    height: 125px;
    background-color: black;
}
</style>