<script setup>
const variants = ref({
    primary: 'primary',
    secondary: 'secondary'
})
const props = defineProps({
    variant: {
        type: String,
        default: 'primary',
    },
    href: {
        type: String,
        required: true
    }
})

</script>

<template>
    <a :href="props.href" target="_blank"
        :class="['items-center text-[16px] flex justify-center gap-[8px] py-[12px] w-full font-bold', { 'bg-[#FFFFFF77] border-[#705F5F70] border-[1px] text-[#141414]': props.variant === variants.secondary }, { 'bg-[#141414] text-white': props.variant === variants.primary }]">
        <slot />
    </a>
</template>

<style>
a {
    font-family: Cambay
}
</style>