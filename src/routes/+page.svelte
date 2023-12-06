<script lang="ts">
	export let data;
</script>

<div class="text-center pt-[42vh]">
	<h1 class="text-6xl font-bold mb-6">{data.post.title}</h1>
	<div class="font-medium text-xl">{@html data.post.content}</div>
</div>
