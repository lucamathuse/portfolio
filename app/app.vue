<template>
  <div>
    <Hero>LUCA <br /> MATHUSE</Hero>
    <Text id="über-mich">
      <template v-slot:title>
        (Über mich)
      </template>
      <template v-slot:text>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
      </template>
    </Text>
    <Stack>(Techstack)</Stack>
    <Accordion id="projekte">(Projekte)</Accordion>
    <Contact>(Kontakt)</Contact>
    <Footer></Footer>
  </div>
</template>
