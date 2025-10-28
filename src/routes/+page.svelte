<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import CustomerCardHero from "$lib/components/layout/hero-sections/CustomerCardHero.svelte";
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
	generating
	title="What we do"
	text="Our technology delivers measurable results through secure, adaptable solutions that directly increase productivity and drive growth."
/>

<Testimonials
	generating
	testimonials={[
		{
			name: "Jane Smith",
			position: "CTO",
			company: "Tech Innovations",
			quote:
				"Their cutting-edge automation boosted our productivity by 35%.\nThe intuitive interface reduced training time and improved team adoption.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "John Doe",
			position: "Director of Operations",
			company: "Global Solutions",
			quote:
				"Their robust security protocols gave us confidence in handling sensitive data.\nThe 24/7 support team resolved issues within hours, not days.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "Sarah Johnson",
			position: "Product Manager",
			company: "Future Systems",
			quote:
				"The scalable platform grew seamlessly with our business needs.\nTheir customization options allowed us to tailor solutions perfectly to our workflows.",
			image: "https://www.unc.mn/image-placeholder.svg"
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
