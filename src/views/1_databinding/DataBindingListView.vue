<template>
  <div>
    <div>
        <select name="" id="">
            <option value="아무거나넣어도됨">아무거나</option>
            <option :value="city.code" :key="city.code" v-for="city in cities">{{city.title}}</option>
        </select>
    </div>
  </div>
</template>

<script>
export default {
    components: {},
    data() {
        return {
            cities: [
                {title: '서울', code: '02'},
                {title: '부산', code: '051'},
                {title: '제주', code: '064'}
            ]
        }
    }
}
</script>

<style>

</style>