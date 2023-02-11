<template>
    <div>
        <li class="item-ref hidden items-center rounded-xl w-fit px-4 py-2 mb-2">
            <slot/>
            {{skill}}
        </li>
    </div>
</template>

<script setup>
import { ref, onMounted } from 'vue';

const props = defineProps(['skill'])

onMounted(() => {
    var className = document.getElementsByClassName('item-ref');
   for(var index=0;index < className.length;index++){
      className[index].classList.add("load-list");
      className[index].classList.remove("hidden");
      className[index].classList.add("flex");
   }
});

</script>

<style scoped>

	/* GLOBAL LOADING ANIMATION FOR ALL PAGES */
	.load-list {
		animation-duration: 4s;
		animation-name: fade-in-load;
		animation-timing-function: cubic-bezier(0.165, 0.84, 0.44, 1);
	}

	@keyframes fade-in-load {
	from {
		opacity: 0;
		transform: translateY(100px);
	}

	to {
		opacity: 1;
		transform: translateY(0);
	}
	}
</style>