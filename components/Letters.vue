<template>
  <div class="letter-grid">
    <div v-for="letter in letters" :key="letter" class="letter d-flex justify-content-center align-items-center p-3 rounded-lg bg-secondary">{{letter}}</div>
</div>
</template>

<script>
export default {
    name: 'letters',
    data(){
        return{
            letters: []
        }
    },
    computed: {
        generatedLetters(){
            let letter, i,a;
            return a=[...Array(26)].map(_=>String.fromCharCode(i++),i=97)
        }
    },
    mounted(){
        this.letters = this.generatedLetters
    }
}
</script>

<style scoped>
.letter{
    /* width: 50px;
    height: 50px; */
    text-transform: uppercase;
}
.letter-grid{
    display: grid;
    grid-template-columns: repeat(11, 1fr);
    gap: 15px;
}
@media screen and (max-width:500px) {
    .letter-grid{        
        grid-template-columns: repeat(6, 1fr);
        gap: 15px;
    }
}
</style>