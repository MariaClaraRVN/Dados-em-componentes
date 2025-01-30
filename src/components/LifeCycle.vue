<template>
    <div>
        <h1>Meu nome é {{ nome }}</h1>
    </div>
</template>

<script>
    export default{
        name: 'LifeClycle',
        data(){
            return{
                nome: 'Maria Clara'
            }
        },
        created(){                  /* Após a criação do componente, algo acontecerá */
            setTimeout(() =>{       /* Tempo de espera para poder ver trocando o nome/
                this.nome = "Rezende"   /* Evento que mudou o dado da variavel nome */
            }, 1000)
        },
        mounted(){
            setTimeout(() =>{       /* Tempo de espera para poder ver trocando o nome, consequentemente, esse será o ultimo nome a aparecer*/
                this.nome = "Vianna"    /* Evento que também substiruiu as duas ultimas variaveis. Evento que mudou o dado da variavel nome */
            }, 2000)
            
        }
    }
</script>

<style scoped> 
</style>