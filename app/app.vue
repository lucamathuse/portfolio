<template>
  <div>
    <Hero>LUCA <br /> MATHUSE</Hero>
    <Text id="über-mich">
      <template v-slot:title>
        (Über mich)
      </template>
      <template v-slot:text>
        Hi! Ich bin Luca, ein (Junior) Fullstack-Entwickler mit Fokus auf Frontend-Entwicklung. Seit fast 3 Jahren erstelle, warte und erweitere ich Websites für Kunden aus den unterschiedlichsten Branchen. Dabei lege ich Wert auf Sorgfalt und sauberen Code, damit alles reibungslos funktioniert.  
      </template>
    </Text>
    <Stack>(Techstack)</Stack>
    <Accordion id="projekte">(Projekte)</Accordion>
    <Contact>(Kontakt)</Contact>
    <Footer></Footer>
  </div>
</template>
