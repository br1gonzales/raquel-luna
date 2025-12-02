<template>
    <section class="h-full">
        <HeroBackground />
        <div
            class="z-[100] absolute w-full h-screen xl:top-[106px] xl:left-[168px] lg:top-[110px] lg:left-[56px] md:top-[189px] sm:top-[173px]xs:top-[166px] xxs:top-[166px] top-[166px]">
            <div class="mx-auto xl:max-w-[1179px] lg:max-w-[1040px] relative flex flex-col gap-[48px]">
                <h1
                    class="text-[#141414] mx-[24px] lg:max-w-[594px] sm:text-[62px] lg:mx-0 sm:leading-[68px] text-[42px] leading-[42px] xl:text-left text-center z-[100] xl:pt-[115px] lg:pt-[109px]">
                    Página en
                    construcción</h1>
                <div
                    class="flex flex-col sm:z-[100] xl:max-w-[594px] lg:max-w-[594px] lg:flex-row xl:gap-[32px] gap-[24px] sm:mx-[75px] lg:mx-0 mx-[24px]">
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
                <NuxtImg width="547" height="663"
                    class="z-10 sm:block hidden absolute xl:top-0 xl:right-0 xl:w-[547px] xl:h-[663px] lg:w-[537px] lg:h-[652px] w-[547px] h-[663px] md:-right-[230px] md:top-[113px]  lg:top-0 lg:right-0 sm:top-[50px] sm:-right-[234px]"
                    src="/vestido.png" alt="vestido" />
            </div>

        </div>
    </section>
</template>

<style>
h1 {
    font-family: Belleza
}
</style>