<template>
    <section class="relative h-full">
        <div class="h-full top-0 left-0 w-full absolute">
            <NuxtImg src="/xl-hero-bg.png" width="1440" class="w-full h-full object-left object-cover" height="714" />
            <img>
        </div>
        <div
            class="z-[100] flex flex-col w-full xl:pt-[115px] xl:pl-[168px] sm:p-[79px_0_0]  p-[174px_0]  z-100 relative gap-[48px]">
            <h1
                class="text-[#141414] mx-[24px] sm:text-[62px] sm:leading-[68px]  text-[42px] leading-[42px] text-center">
                Página en
                construcción</h1>
            <div class="flex flex-col xl:gap-[32px] gap-[24px] sm:mx-[75px] mx-[24px]">
                <LinkButton variant="primary" href="https://wa.me/+51996858080">
                    <img src="/whatsapp.png" alt="whatsapp logo" width="24" height="24">
                    <span class="mt-[4px]">Sacar cita
                        por
                        Whatsapp</span>
                </LinkButton>
                <LinkButton variant="secondary" href="https://www.instagram.com/raquelluna.atelier/">
                    <img src="/instagram.png" width="24" height="24" alt="instagram logo">
                    <span class="mt-[4px]">Ir a Instagram</span>
                </LinkButton>
            </div>
        </div>
        <NuxtImg width="547" height="663"
            class="z-50 sm:block hidden absolute w-[547px] h-[663px] md:-right-[230px] md:-bottom-[138px] sm:-right-[238px] sm:-bottom-[78px]"
            src="/vestido.png" alt="vestido" />
    </section>
</template>

<style>
h1 {
    font-family: Belleza
}
</style>