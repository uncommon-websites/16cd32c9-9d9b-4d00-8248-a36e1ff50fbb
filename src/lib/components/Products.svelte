<script>
  import SectionLabel from './SectionLabel.svelte';
</script>

<section class="bg-[#f5f5f5] px-6 py-24 border-t border-gray-200" id="vaults">
  <div class="max-w-[1400px] mx-auto grid grid-cols-1 lg:grid-cols-12 gap-12">
    <div class="lg:col-span-3">
      <SectionLabel label="Our Products" />
    </div>
    
    <div class="lg:col-span-9">
      <div class="mb-16" id="strategies">
        <h2 class="font-serif text-4xl md:text-5xl text-gray-900 mb-2">
          DeFi Vaults & CeFi Strategies
        </h2>
        <h2 class="font-serif text-4xl md:text-5xl text-gray-400">
          powered by AI quantitative models
        </h2>
      </div>

      <div class="grid gap-0 border-t border-gray-200">
        <!-- Item 1 -->
        <a href="/" class="group grid grid-cols-1 md:grid-cols-12 gap-6 py-10 border-b border-gray-200 hover:bg-white transition-colors px-4 -mx-4">
          <div class="md:col-span-4">
            <div class="text-xs text-gray-400 mb-1">54.8% APY • $474.7k TVL</div>
            <h3 class="text-2xl font-medium text-gray-900">USDC Alpha Aggressive</h3>
          </div>
          <div class="md:col-span-7">
            <p class="text-gray-500 leading-relaxed">
              High-performance directional strategy leveraging momentum and statistical arbitrage. Ranked #1 on Drift Protocol with institutional-grade risk management.
            </p>
          </div>
          <div class="md:col-span-1 flex justify-end items-start pt-2">
            <svg class="w-6 h-6 text-gray-400 group-hover:text-black transform group-hover:translate-x-1 transition-all" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3"></path></svg>
          </div>
        </a>

        <!-- Item 2 -->
        <a href="/" class="group grid grid-cols-1 md:grid-cols-12 gap-6 py-10 border-b border-gray-200 hover:bg-white transition-colors px-4 -mx-4">
          <div class="md:col-span-4">
            <div class="text-xs text-gray-400 mb-1">15.4% APY • Market Neutral</div>
            <h3 class="text-2xl font-medium text-gray-900">USDC Staking/Neutral JLP</h3>
          </div>
          <div class="md:col-span-7">
            <p class="text-gray-500 leading-relaxed">
              Balanced strategy combining staking yields with market-neutral positions. Lower volatility with consistent returns for conservative investors.
            </p>
          </div>
          <div class="md:col-span-1 flex justify-end items-start pt-2">
            <svg class="w-6 h-6 text-gray-400 group-hover:text-black transform group-hover:translate-x-1 transition-all" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3"></path></svg>
          </div>
        </a>

        <!-- Item 3 -->
        <a href="/" class="group grid grid-cols-1 md:grid-cols-12 gap-6 py-10 border-b border-gray-200 hover:bg-white transition-colors px-4 -mx-4">
          <div class="md:col-span-4">
            <div class="text-xs text-gray-400 mb-1">12.6% APY • Stable Returns</div>
            <h3 class="text-2xl font-medium text-gray-900">Alpha Stable</h3>
          </div>
          <div class="md:col-span-7">
            <p class="text-gray-500 leading-relaxed">
              Conservative earn strategy focused on capital preservation with steady yields. Ideal for risk-averse investors seeking stable passive income.
            </p>
          </div>
          <div class="md:col-span-1 flex justify-end items-start pt-2">
            <svg class="w-6 h-6 text-gray-400 group-hover:text-black transform group-hover:translate-x-1 transition-all" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3"></path></svg>
          </div>
        </a>

        <!-- Item 4 -->
        <a href="/" class="group grid grid-cols-1 md:grid-cols-12 gap-6 py-10 border-b border-gray-200 hover:bg-white transition-colors px-4 -mx-4" id="token">
          <div class="md:col-span-4">
            <div class="text-xs text-gray-400 mb-1">DAO Governance • Tier Access</div>
            <h3 class="text-2xl font-medium text-gray-900">$KVAI Token</h3>
          </div>
          <div class="md:col-span-7">
            <p class="text-gray-500 leading-relaxed">
              Utility token providing tier-based access to premium strategies, DAO voting rights on which hedge fund strategies to tokenize, and exclusive benefits. Audited by two firms.
            </p>
          </div>
          <div class="md:col-span-1 flex justify-end items-start pt-2">
            <svg class="w-6 h-6 text-gray-400 group-hover:text-black transform group-hover:translate-x-1 transition-all" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3"></path></svg>
          </div>
        </a>
      </div>
    </div>
  </div>
</section>
