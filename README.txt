DENTAL 24 – Hosting-Paket
=========================
Hochladen (Inhalt dieses Ordners in das Webroot, z. B. public_html/):
  index.html        -> Deutsche Version  (https://IHRE-DOMAIN/)
  en/index.html     -> Englische Version (https://IHRE-DOMAIN/en/)
  favicon.ico, favicon-32.png, apple-touch-icon.png, icon-192.png

Eingebettet in der HTML-Datei: CSS, JavaScript, Bilder, Lottie-Animationsdaten, Videos, alle Schriften (Inter, Onest, Plus Jakarta Sans, Nunito), Favicon.

NOCH EINZURICHTEN
1. Domain: "https://www.example.ch" in beiden Dateien ersetzen (canonical, hreflang, og:url, og:image, twitter:image).
2. og:image: Bild 1200x630 px hochladen und URL eintragen.
3. Formular -> Google Tabelle: Apps-Script-Web-App-URL in  var SHEET_URL=''  eintragen (beide Dateien).
4. Impressum/Datenschutz: Inhaberdaten, UID, Bewilligung, Hosting-Anbieter ergaenzen; Text rechtlich pruefen.
5. Analytics (optional): Platzhalter <!-- GA4 --> und <!-- Meta Pixel --> im <head>.

EXTERNE DIENSTE
- Lenis (jsDelivr) und lottie-web (cdnjs): Skripte kommen vom CDN; faellt das CDN aus, scrollt die Seite normal
  und die kleinen Icons bei "Krone in 60 Min." erscheinen nicht. (Dateien lokal einbetten -> Datenschutz Ziffer 6 anpassen.)
- Google Maps / Street View (iframe und Links), Apple Maps (Link).

LOGOS UND ICONS
  favicon.ico, favicon-32.png, icon-192.png, icon-512.png, apple-touch-icon.png : aus dem Logo (weisser Zahn auf Markenblau)
  logo.png (blau, fuer helle Flaechen), logo-light-text.png (fuer dunkle Flaechen), logo-white.png (einfarbig weiss)
  og-image.jpg : Vorschaubild 1200x630 fuer Links (Telegram, WhatsApp, Facebook)
