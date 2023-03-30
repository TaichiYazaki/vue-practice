<script>
export default {
    mounted() {
        this.$refs.p.textContent = 'mounted!!!'
    }
}
</script>
<template>
    <div>
        <p ref="p">hello</p>
    </div>
</template>