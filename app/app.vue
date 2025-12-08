<template>
  <div>
    <Hero>LUCA <br /> MATHUSE</Hero>
    <Text id="techstack">
      <template v-slot:title>
        (Techstack)
      </template>
      <template v-slot:text>
        HTML, CSS / SCSS, Tailwind, JavaScript (inkl. Vue.js & Nuxt.js), Playwright, etc.
      </template>
    </Text>
    <Text id="über-mich">
      <template v-slot:title>
        (Über mich)
      </template>
      <template v-slot:text>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
      </template>
    </Text>
    <Accordion id="projekte">(Projekte)</Accordion>
    <Footer></Footer>
  </div>
</template>
