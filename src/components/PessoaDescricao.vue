<template>
    <div>
        <h2>Esta é a descrição da pessoa: <br>
            Seu nome é {{ nome }}, atualmente ela tem {{ idade }}, e está cursando {{ escolaridade }}</h2>
        <InfoUser/> <!-- Puxa um componente para dentro de um outro componente -->
    </div>
</template>

<script>
import InfoUser from './infoUser.vue';

export default{
    name:  'PessoaDescricao',

    components: {           /* Cria-se o padrão para chamr outros componetes */
        InfoUser
    },

    data(){
        return{
            nome: "Maria",
            idade: "22 anos" ,
            escolaridade: "6° Semestre de Jogos Digitais"
        }
    }
}
</script>