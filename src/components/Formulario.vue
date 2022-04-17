<template>
    <form class="form-cadastro" data-aos="zoom-in">
        <h1 class="text-center">Cadastre-se</h1>
        <div class="d-flex flex-wrap">
            <div class="mb-3">
                <input type="text" placeholder="Name" v-model="Name">
            </div>
            <div class="m-1"></div>
            <div class="mb-3">
                <input type="text" placeholder="Phone" v-model="Phone">
            </div>
        </div>
        <div class="d-flex flex-wrap">
            <div class="mb-3">
                <input type="text" placeholder="Email" v-model="Email">
            </div>
            <div class="m-1"></div>
            <div class="mb-3">
                <input type="text" placeholder="City" v-model="City">
            </div>
        </div>
        <button class="btn text-white" type="submit">Enviar</button>
    </form>
</template>
<script>
export default {
    name: 'Formulario',
    data() {
        return {
            Name: '',
            Phone: '',
            Email: '',
            City: '',
            verify: false
        }
    },
    methods: {
        verifForm(){

        }
    },
}
</script>
<style scoped>
    .d-flex{
        display: flex;
    }
    .flex-wrap{
        flex-wrap: wrap;
    }
    .mb-3{
        margin-bottom: 10px;
    }
    .form-cadastro{
        padding: 20px;
        background: rgba(34, 34, 34, 0.9);
        display: inline-block;
        
    }
    .justify-content-between{
        justify-content: space-between;
    }
    .w-100{
        width: 100%;
    }
    .m-1{
        margin: 5px;

    }
    .text-white{
        color: #fff;
    }
    .text-center{
        text-align: center;
    }
    input{
        font-size: 20px;
        height: 40px;
        padding: 0 10px;
    }
    input:focus {
        border: 2px solid rgb(226, 60, 101);
        outline: none;
    }
    .btn{
        background-color: rgb(226, 60, 101);
        border: none;
        padding: 15px;
        width: 100%;
        cursor: pointer;
    }
    h1{
       color: #e23c65;
    }
</style>