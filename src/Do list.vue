<template>
<p class="do-font" style="font-size:17.5px"> <img class="do-shield-image" src="Do and Dont images/Do-shield-image.svg">{{ DoListExp }}</p>
</template>
<script>
export default {
    name: 'DoList',
    props: {
        DoListExp: String
    }
    
}
</script>
<style>
.do-font{
    background:green;
    display:flex;
    border-radius: 10px;
    color:black;
    font-weight: 0;
}
</style>