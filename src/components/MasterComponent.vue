<template>
<div>
    <p>This is the master component</p>
    <router-link :to='detailsPath' >Go to detail</router-link>
</div>
</template>

<script>
export default {
    name: 'MasterComponent',
    data() {
        return {
            detailsPath: '/detail'
        }
    }
}
</script>