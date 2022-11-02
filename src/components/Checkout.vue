<template>
    <div class="box">
        <div class="create">
            <div class="phone">
                <img src="../assets/thirdPhone-removebg-preview.png">
            </div>
            <div class="createText">
                <h4>Checkout</h4>
                <p>When you done check out
                    and get it delivered.</p>
                <span>When you done check out and get it
                    delivered with ease.</span>
            </div>
        </div>
    </div>
</template>



<!-- fddhsfhg -->
<style lang="scss" scoped>
.box {

    background-color: #fff;

    .create {
        margin-top: 60px;
        justify-content: center;
        display: flex;

        .phone {
            margin-right: 80px;

            img {
                width: 80%;
                height: 95%;
                filter: drop-shadow(2px 20px 20px rgba(51, 42, 42, 0.555));
                transition: 0.7s;
                transform-style: preserve-3d;
                transform-origin: right;

                &:hover {
                    transform: scale3d(1.02, 1.02, 1.02);
                }
            }
        }

        .createText {
            display: flex;
            flex-direction: column;
            align-items: flex-start;
            padding-top: 50px;
            width: 568px;
            height: 280px;

            h4 {
                font-family: 'Montserrat';
                font-style: normal;
                font-weight: 700;
                font-size: 24px;
                line-height: 36px;
                letter-spacing: 0.1px;

                color: #0FB3C2;
            }

            p {
                font-family: 'Montserrat';
                font-style: normal;
                font-weight: 700;
                font-size: 40px;
                line-height: 57px;
                letter-spacing: 0.2px;
                color: #252B42;
            }

            span {
                font-family: 'Montserrat';
                font-style: normal;
                font-weight: 500;
                font-size: 24px;
                line-height: 38px;
                letter-spacing: 0.2px;
                color: #737373;
            }
        }
    }

}
</style>>