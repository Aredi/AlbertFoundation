<template>
    <div class="flex   g-background-tertiary">
        <!--Header Alert-->
        <div class="alert-banner">
            <label class=" close cursor-pointer  items-center " title="close" for="banneralerte">
                <input type="checkbox" class="hidden" id="banneralerte">
                <div role=" alert ">
                    <div class=" mx-4 py-2">
                        <div class="text-center bg-red-500 text-white font-bold rounded px-4 ">
                            Under Construction Website ! (click to close)
                        </div>

                </div>
                </div>
            </label>
        </div>
    </div>

</template>

<script>
    export default {
        name: "UnderConstruction"
    }
</script>

<style>

    /*Banner open/load animation*/
    .alert-banner {
        -webkit-animation: slide-in-top 0.5s cubic-bezier(0.250, 0.460, 0.450, 0.940) both;
        animation: slide-in-top 0.5s cubic-bezier(0.250, 0.460, 0.450, 0.940) both;
    }

    /*Banner close animation*/
    .alert-banner input:checked ~ * {
        -webkit-animation: slide-out-top 0.5s cubic-bezier(0.550, 0.085, 0.680, 0.530) both;
        animation: slide-out-top 0.5s cubic-bezier(0.550, 0.085, 0.680, 0.530) both;
    }

    /*Footer open/load animation*/
    .alert-footer {
        -webkit-animation: slide-in-bottom 0.5s cubic-bezier(0.250, 0.460, 0.450, 0.940) both;
        animation: slide-in-bottom 0.5s cubic-bezier(0.250, 0.460, 0.450, 0.940) both;
    }

    /*Footer close animation*/
    .alert-footer input:checked ~ * {
        -webkit-animation: slide-out-bottom 0.5s cubic-bezier(0.550, 0.085, 0.680, 0.530) both;
        animation: slide-out-bottom 0.5s cubic-bezier(0.550, 0.085, 0.680, 0.530) both;
    }

    /*Toast open/load animation*/
    .alert-toast {
        -webkit-animation: slide-in-right 0.5s cubic-bezier(0.250, 0.460, 0.450, 0.940) both;
        animation: slide-in-right 0.5s cubic-bezier(0.250, 0.460, 0.450, 0.940) both;
    }

    /*Toast close animation*/
    .alert-toast input:checked ~ * {
        -webkit-animation: fade-out-right 0.7s cubic-bezier(0.250, 0.460, 0.450, 0.940) both;
        animation: fade-out-right 0.7s cubic-bezier(0.250, 0.460, 0.450, 0.940) both;
    }

    /* -------------------------------------------------------------
    * Animations generated using Animista * w: http://animista.net,
    * ---------------------------------------------------------- */

    @-webkit-keyframes slide-in-top {
        0% {
            -webkit-transform: translateY(-1000px);
            transform: translateY(-1000px);
            opacity: 0
        }
        100% {
            -webkit-transform: translateY(0);
            transform: translateY(0);
            opacity: 1
        }
    }

    @keyframes slide-in-top {
        0% {
            -webkit-transform: translateY(-1000px);
            transform: translateY(-1000px);
            opacity: 0
        }
        100% {
            -webkit-transform: translateY(0);
            transform: translateY(0);
            opacity: 1
        }
    }

    @-webkit-keyframes slide-out-top {
        0% {
            -webkit-transform: translateY(0);
            transform: translateY(0);
            opacity: 1
        }
        100% {
            -webkit-transform: translateY(-1000px);
            transform: translateY(-1000px);
            opacity: 0
        }
    }

    @keyframes slide-out-top {
        0% {
            -webkit-transform: translateY(0);
            transform: translateY(0);
            opacity: 1
        }
        100% {
            -webkit-transform: translateY(-1000px);
            transform: translateY(-1000px);
            opacity: 0
        }
    }

    @-webkit-keyframes slide-in-bottom {
        0% {
            -webkit-transform: translateY(1000px);
            transform: translateY(1000px);
            opacity: 0
        }
        100% {
            -webkit-transform: translateY(0);
            transform: translateY(0);
            opacity: 1
        }
    }

    @keyframes slide-in-bottom {
        0% {
            -webkit-transform: translateY(1000px);
            transform: translateY(1000px);
            opacity: 0
        }
        100% {
            -webkit-transform: translateY(0);
            transform: translateY(0);
            opacity: 1
        }
    }

    @-webkit-keyframes slide-out-bottom {
        0% {
            -webkit-transform: translateY(0);
            transform: translateY(0);
            opacity: 1
        }
        100% {
            -webkit-transform: translateY(1000px);
            transform: translateY(1000px);
            opacity: 0
        }
    }

    @keyframes slide-out-bottom {
        0% {
            -webkit-transform: translateY(0);
            transform: translateY(0);
            opacity: 1
        }
        100% {
            -webkit-transform: translateY(1000px);
            transform: translateY(1000px);
            opacity: 0
        }
    }

    @-webkit-keyframes slide-in-right {
        0% {
            -webkit-transform: translateX(1000px);
            transform: translateX(1000px);
            opacity: 0
        }
        100% {
            -webkit-transform: translateX(0);
            transform: translateX(0);
            opacity: 1
        }
    }

    @keyframes slide-in-right {
        0% {
            -webkit-transform: translateX(1000px);
            transform: translateX(1000px);
            opacity: 0
        }
        100% {
            -webkit-transform: translateX(0);
            transform: translateX(0);
            opacity: 1
        }
    }

    @-webkit-keyframes fade-out-right {
        0% {
            -webkit-transform: translateX(0);
            transform: translateX(0);
            opacity: 1
        }
        100% {
            -webkit-transform: translateX(50px);
            transform: translateX(50px);
            opacity: 0
        }
    }

    @keyframes fade-out-right {
        0% {
            -webkit-transform: translateX(0);
            transform: translateX(0);
            opacity: 1
        }
        100% {
            -webkit-transform: translateX(50px);
            transform: translateX(50px);
            opacity: 0
        }
    }

</style>
