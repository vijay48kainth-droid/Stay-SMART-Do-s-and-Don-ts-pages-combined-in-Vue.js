<template>
<p class="dont-font" style="font-size:18px"><img class="dont-shield-image" src="Do and Dont images/Dont-shield-image.svg">{{ DontListExp }}</p>


</template>
<script>
export default {
    name: 'DontList',
    props: {
        DontListExp: String
    }
    
}
</script>
<style>
.dont-font{
    background:red;
    display:flex;
    border-radius: 10px;
    color:black;
    font-weight:500;
}
</style>