<script>
  import SectionLabel from './SectionLabel.svelte';
</script>

<section class="bg-white px-6 py-24 border-t border-gray-200">
  <div class="max-w-[1400px] mx-auto grid grid-cols-1 lg:grid-cols-12 gap-12">
    <div class="lg:col-span-3">
      <SectionLabel label="Security & Trust" />
    </div>
    
    <div class="lg:col-span-9">
      <h2 class="font-serif text-4xl md:text-5xl text-gray-900 mb-16">
        Built on transparency and security
      </h2>

      <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
        <!-- Feature 1 -->
        <div class="border-l-2 border-gray-200 pl-6">
          <div class="text-sm font-medium text-gray-900 mb-2">Dual Audited</div>
          <p class="text-sm text-gray-500 leading-relaxed">
            All smart contracts audited by two independent security firms to ensure maximum protection of user funds.
          </p>
        </div>

        <!-- Feature 2 -->
        <div class="border-l-2 border-gray-200 pl-6">
          <div class="text-sm font-medium text-gray-900 mb-2">Self-Custody</div>
          <p class="text-sm text-gray-500 leading-relaxed">
            Your assets remain in your wallet. Connect via decentralized protocols—you maintain full control at all times.
          </p>
        </div>

        <!-- Feature 3 -->
        <div class="border-l-2 border-gray-200 pl-6">
          <div class="text-sm font-medium text-gray-900 mb-2">Transparent Performance</div>
          <p class="text-sm text-gray-500 leading-relaxed">
            Real-time on-chain tracking of all strategies. Every trade is verifiable and performance is publicly auditable.
          </p>
        </div>

        <!-- Feature 4 -->
        <div class="border-l-2 border-gray-200 pl-6">
          <div class="text-sm font-medium text-gray-900 mb-2">DAO Governance</div>
          <p class="text-sm text-gray-500 leading-relaxed">
            Token holders vote on which strategies to add, ensuring community-driven development and alignment.
          </p>
        </div>

        <!-- Feature 5 -->
        <div class="border-l-2 border-gray-200 pl-6">
          <div class="text-sm font-medium text-gray-900 mb-2">Institutional Grade</div>
          <p class="text-sm text-gray-500 leading-relaxed">
            Quantitative strategies developed by experienced analysts, tested and optimized for consistent returns.
          </p>
        </div>

        <!-- Feature 6 -->
        <div class="border-l-2 border-gray-200 pl-6">
          <div class="text-sm font-medium text-gray-900 mb-2">24/7 Monitoring</div>
          <p class="text-sm text-gray-500 leading-relaxed">
            Continuous risk management and performance monitoring by our team of quantitative analysts.
          </p>
        </div>
      </div>
    </div>
  </div>
</section>
