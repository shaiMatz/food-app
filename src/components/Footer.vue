<template>
    <div class="hello">
        <p>
            Download the app now.
        </p>
        <span>Available on your favorite store. Start your premium experience now</span>

        <ul>
            <li>
                <div class="download android">
                    <i class="fa fa fa-android fa-2x"></i>
                    <span class="df">Download from</span>
                    <span class="dfn">Google Play</span>
                </div>
            </lI>
            <li>
                <div class="download apple">
                    <i class="fa fa fa-apple fa-2x"></i>
                    <span class="df">Download from</span>
                    <span class="dfn">App Store</span>
                </div>
            </li>
            <li>
                <div class="download windows">
                    <i class="fa fa fa-windows fa-2x"></i>
                    <span class="df">Download from</span>
                    <span class="dfn">Windows Store</span>
                </div>
            </li>
        </ul>
    </div>
</template>
  
<script>
export default {
    name: 'HelloWorld',
    props: {
        msg: String
    }
}
</script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
.hello {
    position: relative;
    text-align: center;
    color: #FFFFFF;
    margin-top: 100px;

    h4 {
        font-family: 'Montserrat';
        font-style: normal;
        font-weight: 700;
        font-size: 24px;
        line-height: 36px;
        /* identical to box height, or 150% */

        text-align: center;
        letter-spacing: 0.1px;

        color: #F7F7F7;
    }

    p {
        font-family: 'Montserrat';
        font-style: normal;
        font-weight: 700;
        font-size: 40px;
        line-height: 57px;
        text-align: center;
        letter-spacing: 0.2px;
        color: #FFFFFF;
    }

    span {
        font-family: 'Montserrat';
        font-style: normal;
        font-weight: 500;
        font-size: 24px;
        line-height: 38px;
        text-align: center;
        letter-spacing: 0.2px;
        color: #F7F7F7;

    }

    ul {
        width: 100%;
        text-align: center;
        margin-top: 100px;
        padding: 0;
        transform: translateY(-50%);
    }

    li {
        display: inline-block;
        margin: 10px;
    }

    .download {
        width: 200px;
        height: 75px;
        background: #0FB3C2;
        float: left;
        box-shadow: 0px 10px 30px rgba(183, 50, 39, 0.2);
        border-radius: 30px;
        position: relative;
        color: #fff;
        cursor: pointer;
        border: 1px solid #fff;
    }

    .download>.fa {
        color: #fff;
        position: absolute;
        top: 50%;
        left: 15px;
        transform: translateY(-50%);
    }

    .df,
    .dfn {
        position: absolute;
        left: 50px;
    }

    .df {
        top: 10px;
        font-size: 14px;
    }

    .dfn {
        top: 28px;
        font-size: 1.08em;
    }

    .download:hover {

        background-color: #FFF;
        border: 1px solid #0FB3C2;

        .df,
        .dfn,
        .fa {
            color: #0FB3C2;
        }
    }


}
</style>
  
  