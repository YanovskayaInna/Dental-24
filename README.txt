DENTAL 24 – Hosting-Paket
=========================
Hochladen (Inhalt dieses Ordners in das Webroot, z. B. public_html/):
  index.html        -> Deutsche Version  (https://IHRE-DOMAIN/)
  en/index.html     -> Englische Version (https://IHRE-DOMAIN/en/)
  favicon.ico, favicon-32.png, apple-touch-icon.png, icon-192.png

Eingebettet in der HTML-Datei: CSS, JavaScript, Bilder, Lottie-Animationsdaten, alle Schriften (Inter, Onest, Plus Jakarta Sans, Nunito), Favicon.

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


VIDEO-ORDNER (wichtig)
Die Videos liegen jetzt als separate Dateien im Ordner "video/" neben index.html:
  hero-720.webm/.mp4 (Handy, Tablet, Laptop), hero-1080.webm/.mp4 (Monitore ab 1500 px),
  krone.webm/.mp4, roentgen.webm/.mp4
Der Ordner "video" muss auf dem Hosting direkt neben index.html liegen (Ordner "en" liegt ebenfalls daneben).
Die Seite ist dadurch nur noch ca. 1,6 MB gross und laedt deutlich schneller.

ORDNER (alle muessen neben index.html liegen): video/, img/, fonts/, en/
Bilder und Schriften liegen jetzt als Dateien in img/ und fonts/ (nicht mehr in der HTML). HTML-Datei ca. 150 KB.
