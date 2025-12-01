<template>
    <section class="relative h-full">
        <div class="h-full top-0 left-0 w-full absolute">
            <NuxtImg src="/xl-hero-bg.png" width="1440" class="w-full h-full object-left object-cover" height="714" />
        </div>
        <div
            class="z-[100] flex flex-col w-full lg:w-[594px] xl:m-[97px_0_0_168px]  lg:m-[108px_0_0_56px] sm:m-[79px_0_0] m-[174px_0_0] z-100 relative gap-[48px]">
            <h1
                class="text-[#141414] mx-[24px] sm:text-[62px] lg:mx-0 sm:leading-[68px] text-[42px] leading-[42px] text-center">
                Página en
                construcción</h1>
            <div class="flex flex-col lg:flex-row xl:gap-[32px] gap-[24px] sm:mx-[75px] lg:mx-0 mx-[24px]">
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
            class="z-50 sm:block hidden absolute xl:bottom-[160px] xl:right-[72px] lg:w-[537px] lg:h-[652px] w-[547px] h-[663px] md:-right-[230px] lg:bottom-[120px] lg:-right-[80px] md:-bottom-[138px] sm:-right-[238px] sm:-bottom-[78px]"
            src="/vestido.png" alt="vestido" />
    </section>
</template>

<style>
h1 {
    font-family: Belleza
}
</style>