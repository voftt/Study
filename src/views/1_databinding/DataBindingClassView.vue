<template>
    <div :class="{'text-red': hasError, active: isActive }">Class Binding</div>
    <div :class="class2">Class Binding2</div>
</template>

<script>
export default {
    components:{},
    data() {
        return {
            isActive: false,
            hasError: false,
            class2: ['active', 'hasError']
        }
    }

}
</script>

<style scoped>
.active {
    background-color: greenyellow;
    font-weight: bold;
}

.text-red {
    color:red;
}
</style>
