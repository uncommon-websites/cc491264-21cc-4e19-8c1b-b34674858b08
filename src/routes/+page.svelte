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
	title="Design that ships"
	text="We help product teams turn their design vision into production-ready features—fast. No translation layers. No endless back-and-forth. Just clean implementation that brings user-centered experiences to life without the usual bottlenecks."
/>

<Testimonials
	testimonials={[
		{
<<<<<<< HEAD
			name: "Carmen Rodriguez",
			position: "VP of Product",
			company: "Velocity Labs",
			quote:
				"We shipped 40% faster by eliminating the handoff chaos between design and engineering. What used to take 3 weeks of back-and-forth now happens in 5 days with zero miscommunication.",
			image: "/generated/image-editorial-style-environmental-portrait-o.webp"
		},
		{
			name: "Marcus Williams",
			position: "Engineering Director",
			company: "Scale Dynamics",
			quote:
				"Our development velocity doubled overnight. The seamless design-to-code workflow saved us 60 hours per sprint and eliminated those costly revision cycles that were killing our timeline.",
			image: "/generated/image-editorial-documentary-portrait-of-a-conf.webp"
		},
		{
			name: "Priya Chen",
			position: "Founder & CEO",
			company: "NextGen Solutions",
			quote:
				"We cut our product development costs by 45% while delivering experiences our users actually love. No more expensive design revisions or engineering rework - just beautiful products that ship on time.",
			image: "/generated/image-environmental-headshot-of-a-confident-as.webp"
=======
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
>>>>>>> 0ffa0a1c4bf854007f88b6f2827dedd2d97d56d0
		}
	]}
/>

<Features
	title="Bridge the gap between vision and reality"
	subtitle="Transform design concepts into production-ready code without losing fidelity or wasting time on handoffs"
	features={[
		{
			title: "Design-to-code translation",
			description: "Convert Figma designs directly into pixel-perfect, production-ready components. Eliminate the 40% time waste from design-engineering miscommunication."
		},
		{
			title: "Real-time collaboration sync",
			description: "Keep designers and developers aligned with live updates, shared component libraries, and instant feedback loops that prevent costly iterations."
		},
		{
			title: "Technical feasibility validation",
			description: "Validate design concepts against engineering constraints before development begins, saving weeks of rework and ensuring realistic timelines."
		},
		{
			title: "Rapid interactive prototyping",
			description: "Build functional prototypes that behave like real products, enabling user testing and stakeholder buy-in before full development investment."
		},
		{
			title: "Component library synchronization",
			description: "Maintain perfect consistency between design systems and code components with automated sync that prevents design drift over time."
		},
		{
			title: "Performance-optimized delivery",
			description: "Ship code that's not just visually accurate but also fast, accessible, and scalable—meeting both design standards and engineering best practices."
		}
	]}
/>
<AboutTeaser generating />
<CallToAction generating />
