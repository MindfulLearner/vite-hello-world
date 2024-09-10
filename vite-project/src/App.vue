<script>
    import Header from './components/Header.vue';
    export default {
        data() {
            return {
                count: 0,
            }
        },
        components: {
            Header
        },
        methods: {
            contaPiu() {
                this.count++;
            }
        }
    }
</script>

<template>
    <Header />
    <div>
        <button @click="contaPiu" type="button"></button>
        <h1>
            {{ count }}
        </h1>
    </div>
</template>

<style scoped>
    * {
        color: white;
    }

    button {
        width: 20px;
        height: 20px;
        background-color: white;
    }
</style>
