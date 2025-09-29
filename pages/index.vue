<template>
  <main class="bg-gray-50 text-gray-900">
    <!-- HERO -->
    <section class="bg-blue-900 text-white text-center py-12 px-6">
      <h1 class="text-4xl font-extrabold leading-tight">
        Sell Your Home for Cash — Fast & Fair
      </h1>
      <p class="mt-3 opacity-90">
        We purchase properties in any condition. No repairs, no open houses.
      </p>
      <button
        class="mt-6 bg-blue-600 hover:bg-blue-700 px-6 py-3 rounded text-lg font-semibold"
        data-tally-open="TALLY_ID_HERE" data-tally-layout="modal"
        data-tally-auto-close="true" data-tally-hide-title="true" data-tally-overlay="true"
        aria-haspopup="dialog">
        GET MY CASH OFFER
      </button>
      <p class="mt-3 text-sm opacity-80">
        Zero fees. Skip agents. You choose when to close.
      </p>
    </section>

    <!-- WHO THIS IS FOR -->
    <section class="max-w-3xl mx-auto py-12 px-6 text-center">
      <img src="/logo.png" alt="Eagle RE Properties" class="mx-auto mb-6 w-28" />
      <h2 class="text-2xl font-bold mb-4">
        Perfect for Owners Who Want a Hassle‑Free Sale
      </h2>
      <ul class="text-left max-w-md mx-auto space-y-2">
        <li>✔ Inherited a property you’d rather not keep</li>
        <li>✔ Facing payment issues or foreclosure worries</li>
        <li>✔ Life changes—relocation, divorce, or downsizing</li>
        <li>✔ Landlord tired of repairs or troublesome tenants</li>
        <li>✔ House needs work you don’t want to handle</li>
        <li>✔ Want a private sale without showings or listings</li>
      </ul>
      <button
        class="mt-6 bg-blue-600 hover:bg-blue-700 px-6 py-3 rounded text-lg font-semibold text-white"
        data-tally-open="TALLY_ID_HERE" data-tally-layout="modal"
        data-tally-auto-close="true" data-tally-hide-title="true" data-tally-overlay="true">
        GET MY CASH OFFER
      </button>
    </section>

    <!-- WHY CHOOSE US -->
    <section class="bg-white py-12 px-6">
      <h2 class="text-2xl font-bold text-center mb-6">
        Why Sellers Trust Eagle RE
      </h2>
      <div class="max-w-3xl mx-auto">
        <img src="/hero.jpg" alt="Selling home costs example" class="rounded w-full shadow" />
        <p class="mt-4 text-center opacity-80">
          We bring clarity and close on your schedule. No pressure, just honest offers.
        </p>
      </div>
    </section>

    <!-- COMPARISON -->
    <section class="bg-gray-50 py-12 px-6">
      <h2 class="text-2xl font-bold text-center mb-6">
        Compare Listing vs. Selling Directly
      </h2>
      <div class="grid md:grid-cols-2 gap-8 max-w-4xl mx-auto">
        <div class="p-6 border rounded-lg bg-white">
          <h3 class="text-xl font-bold mb-3">Traditional Listing</h3>
          <ul class="space-y-2 text-red-600">
            <li>✘ Open houses, showings & staging</li>
            <li>✘ Price reductions & negotiation delays</li>
            <li>✘ 5–6 % agent commissions & fees</li>
            <li>✘ Uncertain closing date</li>
          </ul>
        </div>
        <div class="p-6 border rounded-lg bg-white">
          <h3 class="text-xl font-bold mb-3">Direct Cash Sale</h3>
          <ul class="space-y-2 text-green-700">
            <li>✔ Offer within one business day</li>
            <li>✔ Sell exactly as it stands—no repairs</li>
            <li>✔ You choose the closing date</li>
            <li>✔ Zero commissions or hidden costs</li>
          </ul>
        </div>
      </div>
      <div class="text-center mt-8">
        <button
          class="bg-blue-600 hover:bg-blue-700 px-6 py-3 rounded text-lg font-semibold text-white"
          data-tally-open="TALLY_ID_HERE" data-tally-layout="modal"
          data-tally-auto-close="true" data-tally-hide-title="true" data-tally-overlay="true">
          GET MY CASH OFFER
        </button>
      </div>
    </section>

    <!-- TESTIMONIALS -->
    <section class="py-12 bg-white px-6 text-center">
      <h2 class="text-2xl font-bold mb-6">
        Hear From Recent Sellers
      </h2>
      <p class="mb-2">
        ⭐⭐⭐⭐⭐ “The sale was stress‑free and transparent. They kept every promise.”
      </p>
      <p>
        ⭐⭐⭐⭐⭐ “I didn’t have to fix anything—closed in two weeks on my timeline.”
      </p>
    </section>

    <!-- HOW IT WORKS -->
    <section class="py-12 px-6 bg-gray-50 text-center">
      <h2 class="text-2xl font-bold mb-8">Our Simple Three‑Step Process</h2>
      <div class="grid md:grid-cols-3 gap-6 max-w-4xl mx-auto">
        <div>
          <h3 class="font-bold">1) Request Your Offer</h3>
          <p>Tell us about your property—just the address and basics.</p>
        </div>
        <div>
          <h3 class="font-bold">2) Review Your Cash Proposal</h3>
          <p>We send a fair cash offer within 24 hours and answer any questions.</p>
        </div>
        <div>
          <h3 class="font-bold">3) Close When You’re Ready</h3>
          <p>You pick the closing date; we handle the paperwork and pay you directly.</p>
        </div>
      </div>
      <button
        class="mt-6 bg-blue-600 hover:bg-blue-700 px-6 py-3 rounded text-lg font-semibold text-white"
        data-tally-open="TALLY_ID_HERE" data-tally-layout="modal"
        data-tally-auto-close="true" data-tally-hide-title="true" data-tally-overlay="true">
        GET MY CASH OFFER
      </button>
    </section>

    <!-- FOOTER -->
    <footer class="mt-10 text-center text-sm opacity-70 py-8">
      <p>Eagle RE Properties • Cincinnati & Northern Kentucky</p>
      <p><a class="underline" href="/privacy">Privacy Policy</a></p>
    </footer>

  </main>
</template>

<script setup>
// no script needed — Tally handles modal internally
</script>

<!-- Tally widget -->
<script defer src="https://tally.so/widgets/embed.js"></script>
