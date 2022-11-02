<template>
    <div class="box">
        <div class="insideBox"></div>
    </div>
    <img id="Pimage" src="../assets/foodPhones-removebg-preview.png">

</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.box {
    /* phone mock up drop shadow */
    background-color: #FFF;
    position: relative;
    bottom: 0;
    height: 600px;
    width: 100%;

    .insideBox {
        height: calc(100% - 100px);
        width: 50%;
        margin-left: auto;
        margin-right: auto;
        border-bottom: 3px solid #E4E4E4;
    }
}

#Pimage {
    filter: drop-shadow(5px 30px 30px rgba(24, 22, 22, 0.452));
    z-index: 1;
    position: absolute;
    top: -90px;
    left: calc(50% - 256px);
    transition: 0.7s;
    transform-style: preserve-3d;
    transform-origin: right;

    &:hover {
        transform: scale3d(1.02, 1.02, 1.02);
        left: calc(50% - 236px);
    }
}
</style>>