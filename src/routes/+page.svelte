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
	import IconBrain from "~icons/lucide/brain";
	import IconWorkflow from "~icons/lucide/workflow";
	import IconShieldCheck from "~icons/lucide/shield-check";
	import IconBlocks from "~icons/lucide/blocks";
	import IconHeadset from "~icons/lucide/headset";
	import IconLock from "~icons/lucide/lock";
</script>

<CustomerCardHero
	title="The AI platform for legal work"
	subtitle="Harvey accelerates legal work through domain-trained AI models trusted by 50 of the top 100 law firms and 74,000+ lawyers worldwide."
	centered={true}
	customers={[
		{
			name: "Dr. Claudia Junker",
			position: "General Counsel, Deutsche Telekom AG",
			imageSrc: "/generated/image-editorial-style-environmental-portrait-o.webp"
		},
		{
			name: "David Wakeling",
			position: "Global Head of Markets Innovation, A&O Shearman",
			imageSrc: "/generated/image-editorial-environmental-portrait-of-a-pr.webp"
		},
		{
			name: "Sarah Mitchell",
			position: "Managing Partner, Reed Smith",
			imageSrc: "/generated/image-editorial-documentary-portrait-of-a-prof.webp"
		},
		{
			name: "Jennifer Anderson",
			position: "Partner, Allen & Overy",
			imageSrc: "/generated/image-editorial-portrait-of-a-professional-fem.webp"
		}
	]}
	callsToAction={[
		{
			href: "/contact",
			label: "Request demo"
		}
	]}
/>
<LogoScroller
	label="Trusted by industry leaders"
	logoUrls={[
		'https://cdn.brandfetch.io/pwc.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/telekom.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/allenovery.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/kkr.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="Built for the complexity of legal work"
	text="Harvey combines domain-specific AI models with agentic workflows to deliver expert-quality work product across contract review, due diligence, legal research, and document analysis. Unlike general-purpose AI tools, our platform is purpose-built for the precision and security requirements of the legal profession, with zero training on customer data and 24/7 white glove support. From elite law firms to Fortune 500 legal departments, we're accelerating how the world's leading legal professionals work."
/>

<Testimonials
	testimonials={[
		{
			name: "Priya Mehta",
			position: "Managing Partner",
			company: "Global Corporate Law",
			quote:
				"Harvey reduced our contract review time from 6 hours to 45 minutes per matter. Our team now handles 3x the volume without adding headcount, directly increasing our billable capacity by $2.3M annually.",
			image: "/generated/image-editorial-style-environmental-portrait-o.webp"
		},
		{
			name: "Marcus Thompson",
			position: "General Counsel",
			company: "Fortune 500 Technology",
			quote:
				"The domain-specific accuracy eliminated our regulatory compliance risks. Harvey caught critical clauses our team missed in due diligence, preventing a potential $8M exposure on our last acquisition.",
			image: "/generated/image-editorial-style-portrait-of-a-profession.webp"
		},
		{
			name: "Jennifer Chen",
			position: "Chief Legal Officer",
			company: "International Financial Services",
			quote:
				"We scaled our legal operations across 12 jurisdictions without proportional cost increases. Harvey's workflow automation delivered 60% cost savings while maintaining the expert-quality output our board demands.",
			image: "/generated/image-editorial-style-environmental-portrait-o.webp"
		}
	]}
/>

<Features
	title="Built for legal excellence"
	subtitle="Domain-specific AI trained exclusively for complex legal work, delivering expert-quality results that transform how you practice law."
	features={[
		{
			title: "Domain-specific AI models",
			description:
				"Purpose-built models trained exclusively for legal work deliver expert-quality analysis that understands the nuances of law, not generic responses. Our multi-model architecture produces work product that matches the sophistication your clients expect.",
			icon: IconBrain
		},
		{
			title: "Agentic workflows",
			description:
				"Automated workflows handle complex legal tasks from contract review to due diligence, dramatically reducing manual effort while maintaining precision. Transform hours of research into minutes without sacrificing quality or accuracy.",
			icon: IconWorkflow
		},
		{
			title: "Privacy-first architecture",
			description:
				"Zero training on customer data means your confidential information stays yours. Enterprise-grade security with industry-standard protection ensures compliance with the strictest legal and regulatory requirements.",
			icon: IconLock
		},
		{
			title: "Custom workflow builder",
			description:
				"Design and deploy custom workflows tailored to your firm's specific practice areas and processes. Adapt Harvey to match your unique way of working rather than forcing your team to change.",
			icon: IconBlocks
		},
		{
			title: "Seamless integrations",
			description:
				"Work where you already do with native Microsoft ecosystem integration across Word, Outlook, and SharePoint. Harvey fits into your existing tools rather than requiring you to learn new platforms.",
			icon: IconBlocks
		},
		{
			title: "White glove support",
			description:
				"24/7 dedicated customer support ensures your team maximizes value from day one. Our support team resolves issues immediately and helps you discover new ways to transform your practice.",
			icon: IconHeadset
		}
	]}
/>
<AboutTeaser />
<CallToAction
	title="Join the legal profession's transformation"
	subtitle="50 of the AmLaw 100 are already ahead"
	description="While your competitors accelerate with domain-specific AI, every day without Harvey means billable hours lost to manual work and strategic opportunities missed. Join 700+ leading law firms and enterprises who've already transformed their practice with professional-class AI built exclusively for legal work."
	imageSrc="/generated/image-editorial-style-environmental-portrait-o.webp"
	callsToAction={[
		{
			href: "/contact",
			label: "Request demo",
			variant: "primary"
		},
		{
			href: "/about",
			label: "Learn more",
			variant: "secondary"
		}
	]}
/>
