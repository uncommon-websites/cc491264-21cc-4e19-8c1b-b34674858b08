<script lang="ts">
	import SectionHeader from "$lib/components/layout/SectionHeader.svelte";

	let {
		title,
		subtitle,
		imageSrc = "https://www.unc.mn/image-placeholder.svg",
		...rest
	}: {
		title: string;
		subtitle: string;
		imageSrc: string;
		[key: string]: any;
	} = $props();
</script>

<header class={[
	"relative overflow-hidden border-b border-gray-100 dark:border-gray-900",
	"bg-gradient-to-br from-primary-600 via-primary-500 to-primary-400"
]} {...rest}>
	<!-- Background gradient overlay -->
	<div class="absolute inset-0 bg-gradient-to-r from-primary-600/90 to-primary-500/80"></div>
	
	<div class="relative text-title3 section-px section-py container mx-auto grid gap-16 gap-y-0">
		<div class={[
			"section-pb-sm container-sm grid text-balance text-primary-50",
			"text-display"
		]}>
			<h1 class="font-semibold tracking-tight">
				{title}
			</h1>
			<p class="text-primary-100 text-xl leading-relaxed">
				{subtitle}
			</p>
		</div>
		
		<div class="aspect-video overflow-clip rounded-xl bg-white/10 backdrop-blur-sm border border-white/20">
			<img
				class="h-full w-full object-cover"
				src={imageSrc}
				alt="Team collaboration in design and development workspace"
			/>
		</div>
	</div>
</header>
