<template>
	<button>
		<mdt-label></mdt-label>
	</button>
</template>

<script lang="ts">
import {defineComponent} from "vue";
import MdtLabel from "./MdtLabel";

export default defineComponent({
	name: "MdtButton",
	components: {MdtLabel}
});

</script>

<style scoped>

</style>
