<script>
  import Navbar from '$lib/components/Navbar.svelte';
  import Hero from '$lib/components/Hero.svelte';
  import Logos from '$lib/components/Logos.svelte';
  import WhyKvants from '$lib/components/WhyKvants.svelte';
  import Security from '$lib/components/Security.svelte';
  import Products from '$lib/components/Products.svelte';
  import Founders from '$lib/components/Founders.svelte';
  import FAQ from '$lib/components/FAQ.svelte';
  import BottomCTA from '$lib/components/BottomCTA.svelte';
  import Footer from '$lib/components/Footer.svelte';
</script>

<svelte:head>
  <title>Kvants - AI-Powered Quantitative Trading for Crypto Investors</title>
  <meta name="description" content="Access institutional-grade quantitative trading strategies via AI. Starting at $500, secured by dual audits. $21M AUM, 1,150+ active users, 17.5% average APY." />
</svelte:head>

<div class="min-h-screen bg-[#f5f5f5] font-sans selection:bg-black selection:text-white">
  <Navbar />
  <Hero />
  <Logos />
  <WhyKvants />
  <Security />
  <Products />
  <Founders />
  <FAQ />
  <BottomCTA />
  <Footer />
</div>

