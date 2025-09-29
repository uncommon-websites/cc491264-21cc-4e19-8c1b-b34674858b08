<script lang="ts">
	// Components
	import CallToAction from "$lib/components/layout/CallToAction.svelte";

	// Icons
	import Story from "./Story.svelte";
	import SecondaryHero from "$lib/components/layout/hero-sections/SecondaryHero.svelte";
	import Culture from "$lib/components/layout/Culture.svelte";

	// Constants
	const values = [
		{
			title: "Design-first thinking",
			description: "Every solution starts with understanding the user experience, then building the technology to deliver it flawlessly."
		},
		{
			title: "Seamless collaboration",
			description: "Breaking down silos between design and engineering to create products that work as beautifully as they look."
		},
		{
			title: "Speed without compromise",
			description: "Helping teams ship user-centered features faster while maintaining the highest standards of quality and craftsmanship."
		}
	];
</script>

<SecondaryHero
	title="Design meets execution"
	subtitle="Where vision becomes real"
	imageSrc="/generated/image-editorial-style-workspace-scene-featurin.webp"
/>

<!-- Story Section -->
<Story
	paragraphs={[
		"We transform design workflows into seamless product experiences by combining design expertise with full-stack engineering capabilities. Our approach bridges the gap between creative vision and technical execution.",
		"Starting with design-heavy startups, we've captured a significant portion of the product design market by focusing on what matters most: helping teams ship user-centered features faster and more efficiently.",
		"We understand that product managers at growing startups spend too much time translating between design and engineering teams. That's exactly the problem we solve through our integrated approach.",
		"Our mission is simple yet powerful: eliminate the handoff gaps that slow down product development. When design and engineering work as one unified process, innovation accelerates and products succeed."
	]}
/>

<!-- Our Culture Section -->
<Culture {values} />

<!-- Team and investor sections removed - no founder/team/investor information available in company context -->

<!-- CTA Section -->
<CallToAction
	title="Design that ships"
	subtitle="Bridge the gap between design and engineering"
	description="Stop losing 40% of your time in handoffs. Our hybrid design-engineering teams turn your vision into production-ready features—fast, without the usual bottlenecks."
	imageSrc="/generated/image-a-product-manager-and-a-small-group-of-d.webp"
/>
