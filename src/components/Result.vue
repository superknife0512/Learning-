<template>
    <div>
    	<p>Counter is: {{ doubleCounter }}</p>
    	<p>The number of clicks is: {{ stringCounter }}</p>
    	<p>slot for my computed: {{x}}</p>
    </div>
</template>

<script>
	import {mapGetters} from 'vuex';
    export default {
       computed: {
       		...mapGetters([
              		'doubleCounter',
              		'stringCounter',
              	]),
       		x(){
       			return 2*3;
       		}
       	}
    }
</script>