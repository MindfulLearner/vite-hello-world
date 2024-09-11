<script>
    export default {
        data() {
            return {
                message: 'hello mondo'
            }
        }
    }
</script>

<template>
    <div class="ciao">
        <h1>
            {{ message }}
        </h1>
        <div class="swagger">
            <img src="/Expo85_sony.jpg" alt="">
        </div>
    </div>
</template>

<style scoped>
    * {
        color: lightblue;
    }

    img {
        width: 100%;
        height: 100%;
    }

    .swagger {
        width: 300px;
        height: 100px;
    }
</style>
