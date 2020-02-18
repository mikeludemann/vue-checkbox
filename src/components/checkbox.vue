<template lang="html">

	<div class="custom--checkbox">
		<input type="checkbox" :value="value" :name="name" :checked="!!isChecked" @change="e => isChecked = e.target.checked">
	</div>

</template>

<script lang="js">

	export default {
		name: 'CustomCheckbox',
		props: {
			name: {
				type: string,
				required: true
			},
			value: {
				type: string,
				required: true
			},
			isChecked: {
				type: boolean,
				default: false,
				required: true
			}
		},
		mounted () {

		},
		data () {
			return {

			}
		},
		methods: {

		},
		computed: {

		}
	}

</script>

<style scoped lang="scss">
	.checkbox {

	}
</style>
