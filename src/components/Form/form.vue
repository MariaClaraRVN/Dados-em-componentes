<template>
    <div>
        <form action="">
            <div>
                <inputForm/>
            </div>

            <hr>
            <div>
                <inputForm/>
            </div>

            <br>
            <div>
                <inputSubmit/>
            </div>
        </form>
    </div>
</template>

<script>
import inputForm from './input1.vue'
import inputSubmit from './input2.vue'

export default{
    name: 'formInput', 
    components:{
        inputForm,
        inputSubmit
    }
}
</script>