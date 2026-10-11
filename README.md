# Vuurwerk-launcher

Launcher voor de JS Legal Force e-learning **Vuurwerk** ("De boa en optreden bij vuurwerk").

- Dit is alleen de toegangspoort. De cursus zelf staat in de repository [`JSLegalForce/Vuurwerk`](https://github.com/JSLegalForce/Vuurwerk); wijzigingen aan de cursus (pagina's, vragen, eindtoets, afbeeldingen, peildatum) worden daar uitgevoerd.
- De launcher bevat geen inhoudelijke kopie van de e-learning: geen cursusdata, geen vragen, geen eindtoets en geen voortgangslogica. Hij leest of wijzigt de opgeslagen voortgang van de cursus niet.
- Werking (zelfde opzet als de launcher van Seksuele straatintimidatie, `Straatintimidatie-launcher/launcher.html`): de knop "Open e-learning op groot scherm" opent de cursus na een klik in een nieuw venster ter grootte van het scherm (`window.open` met schermbreedte en -hoogte). Blokkeert de browser of leeromgeving nieuwe vensters, dan verschijnt een terugvaloptie: "Open in een nieuw tabblad" of "Open in dit venster" (target `_top`). De knop is ook een gewone link, dus zonder JavaScript opent de cursus in een nieuw tabblad.
- De launcher kan in een leeromgeving (iframe) worden geplaatst. De cursus wordt bewust niet in een iframe geladen: dan zou de voortgang in sommige browsers apart (gepartitioneerd) worden opgeslagen.
- De cursus werkt ook zonder de launcher.

Bestanden: `index.html` (alles in één bestand), `README.md`.

Live launcher: https://jslegalforce.github.io/Vuurwerk-launcher/
Live cursus: https://jslegalforce.github.io/Vuurwerk/

Let op: de juridische peildatum op de launcher (nu 12 oktober 2026) staat los van de cursus. Pas die hier ook aan als de peildatum van de cursus verandert.
