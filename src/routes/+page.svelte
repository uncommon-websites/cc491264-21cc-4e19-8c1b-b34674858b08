<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import Hero from "$lib/components/layout/hero-sections/Hero.svelte";
</script>

<Hero
	title="Bridge design and engineering. Faster."
	subtitle="Ship better product experiences. Without the handoff pain."
	imageSrc="/generated/image-editorial-style-photograph-of-a-product-.webp"
	centered={false}
/>
<LogoScroller 
	label="Trusted by industry leaders" 
	logoUrls={[
		'https://cdn.brandfetch.io/notion.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/vercel.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/airbnb.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/dropbox.com/w/400/h/400/logo'
	]}
/>

<Summary
	generating
	title="What we do"
	text="Our technology delivers measurable results through secure, adaptable solutions that directly increase productivity and drive growth."
/>

<Testimonials
	testimonials={[
		{
			name: "Marcus Chen",
			position: "Product Manager",
			company: "Velocity Labs",
			quote:
				"We cut our design-to-dev handoff time from 3 weeks to 3 days. Their seamless workflow eliminated the constant back-and-forth between our design and engineering teams, letting us ship features 10x faster.",
			image: "/generated/image-editorial-documentary-style-environmenta.webp"
		},
		{
			name: "Priya Sharma",
			position: "Engineering Director",
			company: "Scale Dynamics",
			quote:
				"They eliminated 90% of our technical debt from design inconsistencies. What used to cost us $50K in rework each quarter now runs smoothly with pixel-perfect implementations that our users actually love.",
			image: "/generated/image-editorial-environmental-portrait-of-priy.webp"
		},
		{
			name: "David Rodriguez",
			position: "Founder & CEO",
			company: "Growth Engine",
			quote:
				"Our conversion rate jumped 40% after they rebuilt our user experience. Instead of spending months debugging design-engineering misalignments, we're focusing on what matters: growing our business.",
			image: "/generated/image-editorial-portrait-of-david-rodriguez-la.webp"
		}
	]}
/>

<Features
	generating
	title="Features"
	subtitle="Some features"
	features={[
		{
			title: "Streamlined Workflows",
			description:
				"Automate repetitive tasks and connect systems to improve productivity with our industry-leading 87% time savings."
		},
		{
			title: "Data Analysis",
			description:
				"Extract meaningful insights from your data with powerful analytical tools backed by proprietary AI algorithms that are 3x more accurate than competitors."
		},
		{
			title: "Secure Collaboration",
			description:
				"Work together seamlessly while maintaining strict data privacy standards with our zero-knowledge architecture and military-grade encryption."
		}
	]}
/>
<AboutTeaser generating />
<CallToAction generating />
