<template>
    <div class="EndP">
        <img id="logoF" alt="Vue logo" src="../assets/foodLogo.png">
        <div class="navI">
            <i class="fa fa fa-facebook fa-2x"></i>
            <i class="fa fa fa-instagram fa-2x"></i>
            <i class="fa fa fa-twitter fa-2x"></i>
        </div>
        <p>Copywright 2020 Bella Onojie.com</p>
    </div>
</template>

<script>
export default {

}
</script>
<style lang="scss" scoped>
.EndP {
    width: 100%;
    height: 120px;
    align-self: stretch;
    background: #ffffff;
    padding: 20px;
    bottom: 0;

    .navI {
        position: relative;
        display: flex;
        justify-content: center;
        bottom: calc(50% - 50px);

        .fa {
            color: #0083E7;
            margin-right: 30px;
        }
    }

    #logoF {
        position: relative;
        display: flex;
        flex-direction: column;
        align-items: stretch;
        position: relative;
        top: calc(50% - 30px);
        width: 140px;
        height: 60px;
    }

    p {
        font-family: 'Roboto';
        font-style: normal;
        font-weight: 700;
        font-size: 12px;
        line-height: 18px;
        text-align: right;
        letter-spacing: 0.1px;
        color: #5C5C5C;
        position: relative;
        right: 100px;
    }
}
</style>>