<template>
  <div>
    Some default layout shared across all pages
    <div>
      <NuxtLink to="/about">About</NuxtLink>
      <NuxtLink to="/">Home</NuxtLink>
    </div>
    <slot />
  </div>
</template>
