<template>
    <p>Counter is: {{ result }}</p>
</template>

<script>
    export default {
       computed:{
       		result(){	
       			return this.$store.getters.doubleCounter;
       		}
       }
    }
</script>