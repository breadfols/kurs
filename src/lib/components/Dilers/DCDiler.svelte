<script lang="ts">
	import type { IDiler } from '$lib/database/cars';

	export let diler: IDiler;
</script>

<div class="car-card">
	<div class="shadow">
		<div class="city"></div>
	</div>
</div>

<style>
	.car-card {
		height: 256px;
		width: 460px;
		background: url('/images/diler.png');
		background-size: cover;
		display: flex;
		align-items: flex-end;
		border-radius: 30px;
	}
	.city {
		margin-left: 20px;
	}
	.shadow {
		background: rgba(61, 60, 60, 1);
		width: 460px;
		height: 30px;
		border-bottom-left-radius: 30px;
		border-bottom-right-radius:30px
	}
</style>
