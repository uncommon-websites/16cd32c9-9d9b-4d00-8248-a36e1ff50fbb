<script lang="ts">
  import { slide } from 'svelte/transition';
  
  interface FAQItem {
    question: string;
    answer: string;
  }

  const faqs: FAQItem[] = [
    { question: "How do the AI-powered strategies work?", answer: "Kvants uses advanced quantitative models combining momentum, statistical arbitrage, and market-neutral strategies. Our AI algorithms analyze market data in real-time to execute trades optimized for risk-adjusted returns. All strategies are backtested and continuously monitored by our team of quantitative analysts." },
    { question: "What is the minimum investment?", answer: "The minimum investment is $500, making institutional-grade trading strategies accessible to retail investors. This is significantly lower than traditional hedge fund minimums which typically start at $100,000 or more." },
    { question: "How are my funds secured?", answer: "Your funds remain in your self-custody wallet at all times. Our smart contracts are audited by two independent security firms. We use decentralized oracle integrations for price feeds and transparent on-chain execution. You maintain full control and can withdraw at any time." },
    { question: "What is the $KVAI token used for?", answer: "The $KVAI token provides tier-based access to premium strategies, DAO governance rights to vote on which hedge fund strategies to tokenize next, and exclusive benefits. Token holders participate in platform decisions and can access higher-performing vaults based on their tier level." },
    { question: "What are the different vault strategies?", answer: "We offer multiple strategy types: Market Neutral (balanced risk), Earn (stable yields), Directional (momentum-based), and Statistical Arbitrage. Each vault has different risk/reward profiles, from conservative 12.6% APY stable strategies to aggressive 54.8% APY directional strategies." },
    { question: "Can I withdraw my funds at any time?", answer: "Yes, you maintain full control of your assets through self-custody. Withdrawals can be initiated at any time through your connected wallet. Processing times may vary based on the specific vault strategy and blockchain network conditions." },
    { question: "What blockchain networks do you support?", answer: "Kvants is built primarily on Solana for fast, low-cost transactions. We integrate with leading DeFi protocols including Drift Protocol and Jupiter. USDC is the primary deposit asset, with support for ETH, BTC, and SOL across various strategies." }
  ];

  let openIndex: number | null = null;

  function toggle(index: number) {
    openIndex = openIndex === index ? null : index;
  }
</script>

<section class="bg-[#f5f5f5] px-6 py-24 border-t border-gray-200">
  <div class="max-w-[1400px] mx-auto grid grid-cols-1 lg:grid-cols-12 gap-12">
    <div class="lg:col-span-4">
      <h2 class="font-serif text-4xl text-gray-900 mb-6">
        Frequently asked questions
      </h2>
      <p class="text-sm text-gray-500 mb-4">
        Everything you need to know about Kvants and our AI-powered trading strategies.
      </p>
      <a href="/" class="text-sm text-gray-900 border-b border-gray-300 pb-0.5 hover:border-black transition-colors">Contact support</a>
    </div>
    
    <div class="lg:col-span-8">
      <div class="border-t border-gray-200">
        {#each faqs as faq, i}
          <div class="border-b border-gray-200">
            <button 
              class="w-full py-6 flex justify-between items-center text-left hover:bg-gray-50 transition-colors"
              on:click={() => toggle(i)}
            >
              <span class="text-lg text-gray-800">{faq.question}</span>
              <span class="text-2xl font-light text-gray-400 ml-4">
                {openIndex === i ? '−' : '+'}
              </span>
            </button>
            {#if openIndex === i}
              <div transition:slide class="pb-6 text-gray-500 leading-relaxed">
                {faq.answer}
              </div>
            {/if}
          </div>
        {/each}
      </div>
    </div>
  </div>
</section>
