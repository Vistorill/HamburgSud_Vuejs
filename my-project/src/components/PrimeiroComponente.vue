<template>
    <div>
        <h1>Ola Vue!!</h1>
        <p>Ola Meu nome é {{nome}} e sou {{profissao}}</p>
    </div>
   
</template>

<script>
export default{
    name:'PrimeiroComponente',
    data(){
        return{
            nome:'Marcos',
            profissao:'Desenvolvedor de softwares'
        }
    }
    
    
}
</script>