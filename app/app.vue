<template>
  <div>
    <Hero>LUCA <br /> MATHUSE</Hero>
    <Text>
      <template v-slot:title>
        (Techstack)
      </template>
      <template v-slot:text>
        HTML, CSS / SCSS, Tailwind, JavaScript (inkl. Vue.js & Nuxt.js), Playwright, etc.
      </template>
    </Text>
    <Text>
      <template v-slot:title>
        (Über mich)
      </template>
      <template v-slot:text>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
      </template>
    </Text>
    <Accordion>(Projekte)</Accordion>
  </div>
</template>
