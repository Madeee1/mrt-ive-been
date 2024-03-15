<template>
    <button class="w-5 h-5 rounded-full outline outline-black" 
        :class="{'bg-green-500': isVisited, 'bg-white': !isVisited}"
        @click="isVisited=!isVisited">
    </button>
</template>
<script>
export default {
	name: "MrtButton",
	data() {
		return {
			isVisited: false,
		};
	},
};
</script>