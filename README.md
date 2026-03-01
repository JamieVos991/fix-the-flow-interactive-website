# Sprint 6 – Technische onderbouwing (CSS & HTML)
## Layout & Responsive 
- Mobile first aanpak: De layout is opgebouwd vanuit mobile en uitgebreid met @media (min-width: 1000px)
- Flexbox en Grid gebruik: Flexbox toegepast voor: Navigatie, Verticale stacks, Card layouts
- Grid toegepast voor: Complexe desktop layouts (section 4)

### Typografie & Schaalbaarheid
- Gebruik van clamp(), bijvoorbeeld: font-size: clamp(2.5rem, 5vw, 4rem);
- max-width voor tekst

### Visuele keuzes
Grid achtergrond
body {
  background: linear-gradient(...);
}

### GSAP animaties

<pre>gsap.from(".intro h1", {
  opacity: 0,
  y: 50,
  duration: 1,
  ease: "power3.out",
});
</pre>

## Toegankelijkheid
- Semantische elementen (header, nav, main, section, article)
- aria-label op menu buttons
- Alt teksten op afbeeldingen
- Focusbare interactieve elementen
- Leesbare line-height 
