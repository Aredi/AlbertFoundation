<template>



    <div class="page-header">
    </div>
</template>

<script>
    export default {
        name: "test"
    }
</script>

<style >

    .page-header {


    }
    .page-header:after {
        animation: grain 8s steps(10) infinite;
        /*background-image: url(https://s3-us-west-2.amazonaws.com/s.cdpn.io/9632/paper-pattern.png);*/
        /*background-image: url("../../assets/img/noise.png");*/
        background-image: url("../../assets/img/grain.gif");
        content: "";
        height: 300%;
        left: -50%;
        /*opacity: 0.5;*/
        opacity: 0.09;
        position: fixed;
        top: -110%;
        width: 300%;
        z-index: 6; /* put .green-box above .dashed-box */
        pointer-events: none;
        filter: brightness(120%);
    }

    @keyframes grain {

        0%, 100% { transform:translate(0, 0) }
        10% { transform:translate(-5%, -10%) }
        20% { transform:translate(-15%, 5%) }
        30% { transform:translate(7%, -25%) }
        40% { transform:translate(-5%, 25%) }
        50% { transform:translate(-15%, 10%) }
        60% { transform:translate(15%, 0%) }
        70% { transform:translate(0%, 15%) }
        80% { transform:translate(3%, 35%) }
        90% { transform:translate(-10%, 10%) }
    }
</style>

