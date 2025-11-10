<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import Hero from "$lib/components/layout/hero-sections/Hero.svelte";

	// Icons
	import IconMail from "~icons/lucide/mail";
	import IconActivity from "~icons/lucide/activity";
	import IconLink from "~icons/lucide/link";
	import IconBrain from "~icons/lucide/brain";
	import IconLayers from "~icons/lucide/layers";
	import IconUsers from "~icons/lucide/users";
</script>

<Hero
	title="Every deal, structured and in sync"
	subtitle="Ferrus transforms scattered emails, spreadsheets, and models into a live workspace where every acquisition stays connected to underwriting."
	imageSrc="/generated/image-a-diverse-commercial-real-estate-team-co.webp"
	centered={false}
/>
<LogoScroller
	label="Trusted by industry leaders"
	logoUrls={[
		'https://cdn.brandfetch.io/blackstone.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/brookfield.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/cbre.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/hines.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="Built for commercial real estate"
	text="Ferrus replaces the chaos of spreadsheets, static CRMs, and buried email threads with an AI-native workspace that captures every deal automatically. Built for acquisitions teams at sponsors and capital partners tracking billions in opportunities, Ferrus keeps your entire pipeline live, structured, and connected directly to underwriting.\n\nStop losing context. Start closing faster."
/>

<Testimonials
	testimonials={[
		{
			name: "Maya Chen",
			position: "Director of Acquisitions",
			company: "Meridian Capital Partners",
			quote:
				"Ferrus cut our deal tracking time from 6 hours to 20 minutes per week. We now have a single source of truth for all 140+ active opportunities, and our team can access underwriting context instantly instead of hunting through email threads.",
			image: "/generated/image-a-professional-asian-woman-dressed-in-sm.webp"
		},
		{
			name: "Marcus Williams",
			position: "VP of Capital Markets",
			company: "Summit Real Estate Group",
			quote:
				"We closed $2.3B in transactions last year and Ferrus saved us from losing track of critical deal terms. The AI capture eliminated manual data entry errors that previously cost us hours in rework and potential deal delays.",
			image: "/generated/image-a-professional-black-man-wearing-an-eleg.webp"
		},
		{
			name: "Sofia Rodriguez",
			position: "Head of Development",
			company: "Ascent Property Ventures",
			quote:
				"Before Ferrus, deals would go cold in spreadsheets while we chased approvals. Now every project stays live with automatic updates from email and models. We identified 3 stalled opportunities worth $85M that we re-engaged within the first month.",
			image: "/generated/image-a-professional-hispanic-woman-dressed-in.webp"
		}
	]}
/>

<Features
	title="Built for the way acquisitions teams actually work"
	subtitle="Stop losing deals in spreadsheets and inboxes. Ferrus brings structure, intelligence, and speed to every acquisition."
	features={[
		{
			title: "Email intelligence that captures every deal",
			description:
				"Ferrus automatically extracts deal terms, key dates, and pricing from broker emails and attachments, eliminating manual data entry and ensuring nothing falls through the cracks.",
			icon: IconMail
		},
		{
			title: "Live workspace where every deal stays current",
			description:
				"Replace static folders and outdated spreadsheets with a dynamic view of your entire pipeline. Every update flows through instantly, keeping your team aligned on what matters.",
			icon: IconActivity
		},
		{
			title: "Direct connection to underwriting",
			description:
				"Push deal data straight into your financial models and pull results back into the workspace. No more version control chaos or disconnected analysis.",
			icon: IconLink
		},
		{
			title: "AI insights on every opportunity",
			description:
				"Get instant context on comparable deals, historical pricing trends, and market positioning without leaving your workflow.",
			icon: IconBrain
		},
		{
			title: "Portfolio view across billions in deals",
			description:
				"Track patterns across your entire pipeline and active assets. Identify what's working, spot emerging opportunities, and make faster strategic decisions.",
			icon: IconLayers
		},
		{
			title: "Team collaboration without context loss",
			description:
				"Everyone sees the same live data, with full audit trails and intelligent notifications that surface what each team member needs to act on.",
			icon: IconUsers
		}
	]}
/>
<AboutTeaser />
<CallToAction
	title="Stop losing deals in spreadsheets"
	subtitle="Get your pipeline into Ferrus in under 30 minutes"
	description="Every day without structure costs you time, context, and closed deals. Join acquisitions teams at leading sponsors who track billions in opportunities with complete visibility and zero manual data entry."
	imageSrc="/generated/image-a-confident-professional-sitting-at-a-sl.webp"
	callsToAction={[
		{
			href: "/contact",
			label: "Schedule a demo",
			variant: "primary"
		},
		{
			href: "/about",
			label: "Learn more",
			variant: "secondary"
		}
	]}
/>
