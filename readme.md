## Hur fungerar CSS-arv?

Vissa egenskaper rinner från förälder till barn, speciellt allt text,
color och font-family. Box Model gör inte det. Padding och
background-color stannar på elementet du stylar.

I vår Hero sätter vi color och font-family på .hero. Då blir h1,
.datum, .plats och .tagline samma färg utan egna regler. När vi
bytte färg på .hero följde alla barn med.
