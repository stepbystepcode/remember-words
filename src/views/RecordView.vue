<template>
	<div class="home">
		<CheckIn />
	</div>
</template>

<script>
// @ is an alias to /src
import CheckIn from "@/components/CheckIn.vue";

export default {
	name: "RecordView",
	components: {
		CheckIn,
	},
};
</script>
