<template>
    <div class="box">
        <h2>How the app works</h2>
        <div class="create">
            <div class="phone">
                <img src="../assets/firstPhone-removebg-preview.png">
            </div>
            <div class="createText">
                <h4>Create an account</h4>
                <p>Create/login to an existing
                    account to get started</p>
                <span>An account is created with your email
                    and a desired password</span>
            </div>
        </div>
    </div>
</template>



<!-- fddhsfhg -->
<style lang="scss" scoped>
.box {
    padding-top:30px ;
    background-color: #fff;

    h2 {
        font-family: 'Poppins';
        font-style: normal;
        font-weight: 600;
        font-size: 44px;
        line-height: 36px;
        text-align: center;
        letter-spacing: 0.1px;
        color: #000000;
        opacity: 0.8;
    }

    .create {
        margin-top:60px;
justify-content: center;
        display: flex;

        .phone {
            margin-right: 80px;
            img {
                width: 80%;
                height: 90%;
                filter: drop-shadow(2px 20px 20px rgba(51, 42, 42, 0.555));
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