<template>
	<div>
		<h4 :class="$style.title">SmallComponent!</h4>
	</div>
</template>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
	name:'SmallComponent',
	created(){
		console.log(this.$style);
	}
})
</script>

<style module>
.title{
	border:dashed 2px #5b8bd0;
	border-radius: 5px;
	padding: 3px;
}
</style>
