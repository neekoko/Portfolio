<template>
    <footer class="footer back-color">
        <div class="container">
            <div class="content has-text-centered float-right">
                <figure class="image is-64x64">
                    <img class="icon-img" src="~/assets/icon.jpg">
                </figure>
            </div>
        </div>
    </footer>
</template>

<style>
    .back-color {
        background-size: cover;
        background-color: #07181c;
        -webkit-clip-path: polygon(0 30%, 100% 0, 100% 100%, 0% 100%);
        clip-path: polygon(0 30%, 100% 0, 100% 100%, 0% 100%);
    }

    .icon-img {
        border-radius: 50%;
    }

    .float-right {
        float: right;
    }
</style>
