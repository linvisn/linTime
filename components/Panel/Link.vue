<template>
    <NuxtLink>
        <PanelButton>
            <slot />
        </PanelButton>
    </NuxtLink>
</template>

<style scoped>
.router-link-active .button {
    background-color: rgb(79, 116, 116);
}
.mocha .router-link-active .button {
    background-color: rgb(var(--ctp-mocha-surface2-rgb)) !important;
}
.midnight-fireplace .router-link-active .button {
  background-color: rgb(98, 105, 0, 0.875) !important;
}
</style>