<a href="https://dekoracijelux.rs/"><img src="media/cover.jpg" alt="Dekoracije Lux, naslovna strana na laptopu i telefonu" width="100%"></a>

# Dekoracije Lux

Sajt za dekoracije proslava iz Šapca: strana za svaku proslavu i vrstu dekoracije, 473 fotografije i upit za termin u sedam koraka.

**[dekoracijelux.rs](https://dekoracijelux.rs/)** · [Studija slučaja](https://svilenkovic.rs/radovi/dekoracije-lux) · [English](README.md)

> [!NOTE]
> Klijentski projekat. Izvorni kod pripada klijentu i čuva se u privatnom repozitorijumu. Ova stranica opisuje šta sam uradio i kako.

<table>
  <tr><td><b>Klijent</b></td><td>Dekoracije Lux</td></tr>
  <tr><td><b>Delatnost</b></td><td>Dekoracije za rođendane, venčanja, krštenja i događaje</td></tr>
  <tr><td><b>Lokacija</b></td><td>Šabac</td></tr>
  <tr><td><b>Vrsta</b></td><td>Sajt sa više strana</td></tr>
  <tr><td><b>Moj deo posla</b></td><td>Dizajn, izrada, SEO, hosting i održavanje</td></tr>
  <tr><td><b>Tehnologije</b></td><td>PHP 8.3, SQLite, Three.js, GSAP, nginx</td></tr>
</table>

## O projektu

Dekoracije Lux su iz Šapca i rade dekoracije za 18. rođendane, venčanja, krštenja, dečije rođendane i korporativne događaje širom Srbije. Ljudi dekoraciju prvo biraju očima, a za termin i cenu pitaju posle, pa sajt prati taj redosled: prave fotografije vode do upita, a upit traži samo ono bez čega predlog ne može da se napravi.

Svaka od sedam proslava i svaka od devet vrsta dekoracije ima svoju stranu, a galerija ima 473 fotografije koje se filtriraju po proslavi i po dekoraciji. Kad se fotografija otvori, jedno dugme je prenosi u formu za upit, koja ide korak po korak i traži samo proslavu, datum i mesto. Na početnoj je 3D scena sa balonima koja se menja dok se skroluje i završava se lukom sa natpisom LUX; crta je Three.js u Web Worker-u, a posetioci sa smanjenim pokretom ili slabijim uređajem dobijaju gotovu sliku iste scene.

## Šta sam uradio

- 21 strana: po jedna za svaku od sedam proslava i devet vrsta dekoracije, uz galeriju, zakazivanje, stranu o nama i kontakt
- Galerija od 473 fotografije sa filterima po proslavi i vrsti dekoracije i dugmetom koje fotografiju prenosi u upit
- Upit u sedam koraka sa karticama sa fotografijama, do tri slike inspiracije i izborom između poziva i mejla, sačuvan u SQLite bazi
- Katalog boja balona na strani o balonima, da se boje navedu u upitu
- Strane napravljene unapred iz PHP šablona, biblioteke sa istog domena i analitika tek posle pristanka
- Mobilni PageSpeed 100 u sve četiri kategorije, izmereno 10. oktobra 2026.

## Merenja

| | Performanse | Pristupačnost | Dobre prakse | SEO |
| :-- | :-: | :-: | :-: | :-: |
| Telefon | 100 | 100 | 100 | 100 |
| Desktop | 100 | 100 | 100 | 100 |

PageSpeed Insights, laboratorijsko merenje živog sajta, oktobar 2026. Sigurnosna zaglavlja: 6 od 6. axe provera pristupačnosti: bez prekršaja. Strukturisani podaci: `FAQPage`, `LocalBusiness`.

## Snimci ekrana

<table>
  <tr>
    <td width="68%" valign="top"><img src="media/desktop.webp" alt="Dekoracije Lux, naslovna strana na ekranu širine 1440 px"></td>
    <td width="32%" valign="top"><img src="media/mobile.webp" alt="Dekoracije Lux, naslovna strana na telefonu"></td>
  </tr>
</table>

<img src="media/inner-1.webp" alt="Galerija od 473 fotografije sa filterima po proslavi i vrsti dekoracije">
<sub>Galerija od 473 fotografije sa filterima po proslavi i vrsti dekoracije</sub>

<img src="media/inner-2.webp" alt="Prvi od sedam koraka upita: izbor proslave na kartici sa fotografijom">
<sub>Prvi od sedam koraka upita: izbor proslave na kartici sa fotografijom</sub>

---

<sub>Izrada: [D. Svilenković](https://svilenkovic.rs).</sub>
