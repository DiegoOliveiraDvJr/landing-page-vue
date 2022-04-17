<template>
    <div class="banner">
        <Formulario />
    </div>
</template>
<script>

import Formulario from './Formulario.vue'

export default {
    components:{
        Formulario
    }
}
</script>
<style scoped>
    .banner{
        width: 100%;
        min-height: 90vh;
        background-image: url(https://images3.alphacoders.com/813/thumb-1920-813087.jpg);
        background-size: cover;
        background-position: center;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }
    
</style>