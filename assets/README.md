# assets

Imaginile pentru profilul `wtshex-ch`.

| Fișier | Ce este | Când se vede |
| --- | --- | --- |
| `emblem-dark.png` | emblema neagră (fundal transparent) | tema **light** |
| `emblem-white.png` | emblema albă (fundal transparent) | tema **dark** |
| `workstation-1.svg` | loc pentru prima foto | stânga |
| `workstation-2.svg` | loc pentru a doua foto | dreapta |

Emblema folosește `<picture>` + `prefers-color-scheme`, deci GitHub alege
automat varianta potrivită pentru tema vizitatorului.

## Înlocuirea pozelor de workstation

Pune cele două fotografii **orizontale (16:9)** peste placeholdere:

- salvează-le ca `workstation-1.jpg` / `workstation-2.jpg`
- în `README.md` schimbă `assets/workstation-1.svg` → `assets/workstation-1.jpg`
  (și la fel pentru a doua)
