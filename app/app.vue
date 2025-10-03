<template>
  <UApp>
    <UHeader title="Emmanuel López">
      <template #right>
        <UColorModeSelect aria-label="Toggle color mode" />
      </template>
    </UHeader>

    <UContainer>
      <NuxtPage />
    </UContainer>

    <USeparator label="by Emmanuel López" />
    <UFooter>The footer</UFooter>
  </UApp>
</template>
