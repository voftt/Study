<template>
  <div>
    <input type="text" name="" id="" v-bind:value="userId" readonly />
    <input type="text" name="" id="" :value="userId" readonly />
    <br>
    <img :src="imgSrc" alt="" style="width: 300px; height: auto">
    <br />
    <input type="search" name="" id="" v-model="txt1" />
    <button :disabled="txt1 ===''">조회</button>
  </div>
</template>

<script>
export default {
    components:{},
    data() {
        return {
            userId: 'changhan',
            imgSrc: 'https://search.pstatic.net/common/?src=http%3A%2F%2Fblogfiles.naver.net%2FMjAyMTEwMDlfMjI0%2FMDAxNjMzNzQzMTI4MDEy.0NwdeVnegkfwtC4gLtMLXN7S6OToCIzbb5D2KbMPwlkg.hJgC7nOZ7M8RtGmAdjRfgyKaRDUlRg1OUFN_i3B1GAEg.JPEG.joepaulchoi%2FScreenshot_20211009-102950_NAVER.jpg&type=sc960_832',
            txt1: ''
        }
    }
}
</script>

<style>

</style>