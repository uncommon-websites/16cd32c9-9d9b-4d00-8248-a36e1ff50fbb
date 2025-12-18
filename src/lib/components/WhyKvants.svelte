<script>
  import SectionLabel from './SectionLabel.svelte';
</script>

<section class="bg-[#f5f5f5] px-6 py-24">
  <div class="max-w-[1400px] mx-auto grid grid-cols-1 lg:grid-cols-12 gap-12">
    <div class="lg:col-span-3">
      <SectionLabel label="Why Kvants" />
    </div>
    
    <div class="lg:col-span-9">
      <div class="mb-12">
        <h2 class="font-serif text-3xl md:text-4xl leading-tight text-gray-900 mb-6">
          Democratizing institutional-grade quantitative trading strategies
        </h2>
        <p class="text-gray-500 leading-relaxed max-w-2xl">
          Advanced AI-powered algorithms previously accessible only to hedge funds, now available to retail crypto investors with transparent, audited smart contracts.
        </p>
      </div>
      
      <div class="grid grid-cols-1 sm:grid-cols-3 gap-6">
        <div class="flex flex-col gap-2 p-6 bg-white rounded border border-gray-200 hover:border-gray-300 transition-colors">
            <span class="text-4xl font-bold text-gray-900">$21M</span>
            <span class="text-xs text-gray-500 uppercase tracking-wider">Assets Under Management</span>
        </div>
        <div class="flex flex-col gap-2 p-6 bg-white rounded border border-gray-200 hover:border-gray-300 transition-colors">
            <span class="text-4xl font-bold text-gray-900">1,150+</span>
            <span class="text-xs text-gray-500 uppercase tracking-wider">Active Users</span>
        </div>
        <div class="flex flex-col gap-2 p-6 bg-white rounded border border-gray-200 hover:border-gray-300 transition-colors">
            <span class="text-4xl font-bold text-gray-900">17.5%</span>
            <span class="text-xs text-gray-500 uppercase tracking-wider">Average APY</span>
        </div>
      </div>
    </div>
  </div>
</section>
