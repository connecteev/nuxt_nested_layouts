<template>
   <div class="">
        <h1>coming from layout 1, line 1</h1>
        <nuxt v-if="!$slots.default" />
        <h1>coming from layout 1, line2</h1>
        <slot />
        <h1>coming from layout 1, line3</h1>
   </div>
</template>
