<template>
  <main>
    <img src="/logo2.svg" alt="DFINITY logo" />
    Siema!!!
    <br>
    {{ licznik }}
    <button @click="podbij">podbij</button>
  </main>
</template>

<script>
export default{
  data(){
    return{
      licznik: 0
    }
  },
  methods:{
    podbij(){
      this.licznik++
    }
  }
}
</script>