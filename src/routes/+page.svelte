<script lang="ts">
	import '../app.css';
	import type { LatLngExpression } from 'leaflet';
	import Leaflet from '$lib/Leaflet.svelte';

	const initialView: LatLngExpression = [51.514244, 7.468429]; // Dortmund, Germany
</script>

<div class="w-full h-screen">
	<Leaflet view={initialView} zoom={12} />
</div>
