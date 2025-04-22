Je kunt de achtergrondafbeelding van een element zo instellen dat andere content ervoor scrolt.

Dit doe je in CSS door het toevoegen van de eigenschap `background-attachment: fixed` aan de selector van het element.

Hier is een voorbeeld:

--- code ---
---
language: css
filename:
line_numbers: true
line_number_start: 1
line_highlights: 4
---

.garden {
  background-image: url("garden.jpeg");
  background-size: cover;
  background-attachment: fixed;
}

--- /code ---

![Een gif die een vaste achtergrondafbeelding laat zien terwijl andere inhoud ervoor scrolt.](images/background-attachment-fixed.gif)
