<template>
  <div class="">
    <input type="text" name="" value="333"/><br/>
    <!-- <input type="text" v-bind:value="nick"/><br/>   -->
    <input type="text" v-model="nick"/><br/>
    <input type="number" v-model.number="age"/><br/>
    <textarea cols="30" rows="10">동해물과 백두산이</textarea><br/>
    <textarea v-model="message" cols="30" rows="10"></textarea><br/>
    <select name="" id="">
          <option value="01">서울</option>
          <option value="02">부산</option>
          <option value="03">대구</option>
          <option value="04" selected>수원</option>
    </select>
     <br/>
       <select name="" id="">
          <option value="01">서울</option>
          <option value="02">부산</option>
          <option value="03 ">대구</option>
          <option value="04">수원</option>
    </select>
  
    
  </div>
</template>

<script>
export default {
  name: 'TestView',
  data(){
    return{
      nick:'노래하는 큰바위',
      age:30,
      massage:'깊은산속'

    };
  },
  mounted() {
    
  },
  unmounted() {
    
  },
  methods: {
    
  }
};
</script>

<style scoped>

</style>