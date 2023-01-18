<script lang="ts">;
	import { browser } from '$app/environment';
	if (browser) {
		// Write browser-only code here
	}
</script>

<textarea />

<svg>
	<rect x="0" y="0" width="100" height="100" fill="red" />
	<rect x="100" y="0" width="100" height="100" fill="green" />
	<rect x="200" y="0" width="100" height="100" fill="blue" />
</svg>

<style>
	textarea {
		width: 45%;
		height: 400px;
		font-family: monospace;
	}

	svg {
		width: 50%;
		height: 400px;
		background: #fff;
	}
</style>
