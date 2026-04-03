# Test Results - Calculator

## Black-box testiranje

| Test | Ulaz | Očekivano | Dobijeno | Napomena |
|------|------|----------|----------|----------|
| 1 | 4+5 | 9 | 9 | OK |
| 2 | 10+5*4 | 30 | 30 | Prioritet operacija ispravan |
| 3 | 10+5*4+3 | 33 | 33 | OK |
| 4 | 10/0 | Greška | Program se ruši | Nema obrade deljenja nulom |
| 5 | abc | Greška | Program se ruši | Nema validacije unosa |
| 6 | 5+ | Greška | Pogrešan rezultat ili crash | Nepotpuni izraz |
| 7 | 10 + 5 | 15 | Ne radi | Razmaci nisu podržani |
| 8 | 5.5+2.2 | 7.7 | Ne radi | Decimalni brojevi nisu podržani |
| 9 | -5+3 | -2 | Ne radi | Negativni brojevi nisu podržani |

## Zaključak

Program ima sledeće nedostatke:
- Nema validaciju ulaza
- Nema obradu grešaka
- Ne podržava sve tipove izraza
- Moguć crash pri deljenju nulom
