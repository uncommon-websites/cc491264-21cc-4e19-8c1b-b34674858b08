<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import CustomerCardHero from "$lib/components/layout/hero-sections/CustomerCardHero.svelte";

	// Icons
	import IconCode2 from "~icons/lucide/code-2";
	import IconUsers from "~icons/lucide/users";
	import IconShieldCheck from "~icons/lucide/shield-check";
	import IconZap from "~icons/lucide/zap";
	import IconLock from "~icons/lucide/lock";
	import IconActivity from "~icons/lucide/activity";
</script>

<CustomerCardHero
	centered={true}
	title="AI agents you can trust"
	subtitle="Build powerful AI agents that automate customer support and internal workflows with no-code visual builder. Trusted by leading developer teams."
	customers={[
		{
			name: "Sarah Chen",
			position: "Head of Developer Relations",
			imageSrc: "/generated/image-editorial-style-portrait-of-a-profession.webp"
		},
		{
			name: "Marcus Rodriguez",
			position: "Product Manager",
			imageSrc: "/generated/image-editorial-environmental-portrait-of-a-pr.webp"
		},
		{
			name: "Emily Thompson",
			position: "Engineering Director",
			imageSrc: "/generated/image-sophisticated-environmental-portrait-of-.webp"
		},
		{
			name: "David Park",
			position: "Technical Lead",
			imageSrc: "/generated/image-editorial-portrait-of-a-professional-man.webp"
		},
		{
			name: "Rachel Foster",
			position: "Support Team Lead",
			imageSrc: "/generated/image-environmental-portrait-of-a-professional.webp"
		}
	]}
/>
<LogoScroller
	label="Trusted by industry leaders"
	logoUrls={[
		'https://cdn.brandfetch.io/anthropic.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/midjourney.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/pinecone.io/w/400/h/400/logo',
		'https://cdn.brandfetch.io/postman.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="What we do"
	text="Inkeep empowers product teams at B2B companies to automate customer support and internal workflows with AI agents they can trust. Our no-code visual builder gives both technical and non-technical teams full control over accuracy through intelligent audit trails and transparent operations. Leading companies like Anthropic, Midjourney, and Solana Foundation rely on Inkeep to scale support without expanding headcount—reducing tickets by up to 48% while increasing user activation."
/>

<Testimonials
	testimonials={[
		{
			name: "Priya Sharma",
			position: "Head of Developer Experience",
			company: "Quantum Labs",
			quote:
				"Inkeep's AI agents resolved 42% of our documentation questions instantly, giving our team back 15 hours per week. The no-code builder let us deploy in days, not months.",
			image: "/generated/image-1-editorial-style-environmental-portrait.webp"
		},
		{
			name: "Marcus Chen",
			position: "VP of Product",
			company: "Velocity Systems",
			quote:
				"The audit trail and transparency features gave us complete confidence in accuracy. We scaled our support capacity 3x without adding headcount, saving $240K annually.",
			image: "/generated/image-2-editorial-documentary-image-of-a-profe.webp"
		},
		{
			name: "Elena Rodriguez",
			position: "Engineering Director",
			company: "Apex Technologies",
			quote:
				"What impressed us most was the two-way sync between visual builder and code. Our engineering and support teams finally collaborate seamlessly, reducing integration time by 60%.",
			image: "/generated/image-3-environmental-portrait-of-a-profession.webp"
		}
	]}
/>

<Features
	title="Built for teams who demand control"
	subtitle="From no-code simplicity to full programmatic control, build AI agents that solve real problems with the trust and transparency your team needs."
	features={[
		{
			title: "No-code meets code",
			description:
				"Build with our visual interface or write code directly—both stay in perfect sync. Engineering and non-technical teams finally work together in one platform without compromise.",
			icon: IconCode2,
			imageSrc: "/generated/image-a-creative-professional-in-a-modern-ligh.webp"
		},
		{
			title: "Multi-agent teams",
			description:
				"Deploy teams of specialized agents that coordinate to handle complex workflows. Watch them break down sophisticated tasks and work together like your best team members.",
			icon: IconUsers,
			imageSrc: "/generated/image-a-diverse-team-of-professionals-in-a-con.webp"
		},
		{
			title: "Trust through transparency",
			description:
				"Every agent decision comes with a complete audit trail and intelligent metrics. See exactly why your AI made each choice, giving you the confidence to deploy at scale.",
			icon: IconShieldCheck,
			imageSrc: "/generated/image-a-group-of-professionals-in-an-airy-arch.webp"
		},
		{
			title: "Deploy everywhere",
			description:
				"One agent, infinite channels—embed in your docs, integrate with Slack, connect to Zendesk, or expose via API. Your customers meet your AI wherever they are.",
			icon: IconZap,
			imageSrc: "/generated/image-several-professionals-in-a-sophisticated.webp"
		},
		{
			title: "Enterprise security",
			description:
				"Automatic PII removal, custom data retention, and credential management that respects user permissions. Security teams sleep well, developers ship fast.",
			icon: IconLock,
			imageSrc: "/generated/image-a-confident-professional-in-a-structured.webp"
		},
		{
			title: "Real-time observability",
			description:
				"Full trace visibility into every agent action with integration to your existing observability tools. Spot issues before customers do and continuously improve performance.",
			icon: IconActivity,
			imageSrc: "/generated/image-a-team-of-professionals-in-an-open-light.webp"
		}
	]}
/>
<AboutTeaser />
<CallToAction
	title="Start building AI agents today"
	subtitle="Join teams from Anthropic, Midjourney, and Solana"
	description="Get started in minutes with our no-code visual builder, or dive deep with full programmatic control. Backed by $13M in funding and trusted by leading developer teams to automate support without compromising on accuracy."
	imageSrc="/generated/image-editorial-style-photograph-of-a-happy-pr.webp"
	callsToAction={[
		{
			href: "https://www.inkeep.com/get-started",
			label: "Start building free",
			variant: "primary"
		},
		{
			href: "https://www.inkeep.com/contact",
			label: "Talk to our team",
			variant: "secondary"
		}
	]}
/>
