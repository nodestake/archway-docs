<script lang="jsx" setup>
  import FeaturedSection from '@/components/Home/FeaturedSection.vue';
</script>

<template>
  <div class="grid pb-16">
    <p class="text-base text-gray-600 mb-4 dark:text-gray-900 leading-[150%]">Featured</p>
    <div class="grid grid-cols-1 lg:grid-cols-2 gap-x-8 gap-y-4">
      <FeaturedSection title="New to Archway?" description="Community Members" url="/getting-started" label="Get Started">
        <img class="w-[115px]" src="@/assets/images/getting-started.png" />
      </FeaturedSection>
      <FeaturedSection
        title="Learn CosmWasm"
        description="Dapp Developers"
        url="/developers/cosmwasm-documentation/introduction"
        label="Documentation"
      >
        <img class="w-[115px]" src="@/assets/images/cosmwasm-documentation.png" />
      </FeaturedSection>
    </div>
  </div>
</template>
