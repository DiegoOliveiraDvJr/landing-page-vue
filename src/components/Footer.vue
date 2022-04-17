<template>
    <footer class="footer">
        <a class="facebook" href="#"></a>
        <a class="instagram" href="#"></a>
        <a class="github" href="#"></a>
    </footer>
</template>
<script>
export default {
    name: 'Footer',
    data() {
         return {

         }   
    },
}
</script>
<style scoped>
    .footer{
        display: flex;
        height: 10vh;
        width: 100%;;
        justify-content: center;
        align-items: center;
        background-color: #fff;
    }
    a{
        width: 32px;
        height: 32px;
        margin: 0 10px;
    }
    .facebook{
        background-image: url('../../public/img/facebook.png');
        background-size: contain;
    }
    .instagram{
        background-image: url('../../public/img/instagram.png');
        background-size: contain;
    }
    .github{
        background-image: url('../../public/img/github.png');
        background-size: contain;
    }

</style>