<template>
    <div>
        <p>I am the detail component</p>
        <button @click="goToMaster">Master</button>
    </div>
</template>

<script>
    export default {
        name: 'DetailComponent',
        methods: {
            goToMaster() {
                this.$router.push('/');
            }
        }
    }
</script>