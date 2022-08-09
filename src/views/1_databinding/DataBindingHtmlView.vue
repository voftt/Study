<template>
  <div>{{ htmlString }}</div>
  <div v-html="htmlString"></div>
</template>

<script>
export default {
    components: {},
    data() {
        return {
          htmlString: '<p style="color:red;">red text</p>'
        }
    }
}
</script>

<style>

</style>