| Fajl            | LOC |
| --------------- | --- |
| Calculator.java | 57  |
| Start.java      | 28  |
| **Ukupno**      | 85  |

| Fajl            | Linija | Zapažanje                                                                  |
| --------------- | ------ | -------------------------------------------------------------------------- |
| Calculator.java | 10     | Metoda evaluateExpression je predugačka i ima više odgovornosti (krši SRP) |
| Calculator.java | 15     | Nedostaje validacija ulaznog izraza (moguć runtime error)                  |
| Calculator.java | 20     | Korišćenje Float umesto double može dovesti do problema sa preciznošću     |
| Calculator.java | 25     | Uslovi u metodi Calculate povećavaju ciklomatsku složenost                 |
| Calculator.java | 30     | Nema obrade izuzetaka (try-catch blok)                                     |
| Calculator.java | 35     | Moguće deljenje nulom nije eksplicitno obrađeno                            |
| Calculator.java | 40     | Metoda Calculate radi više stvari (parsiranje + računanje)                 |
| Calculator.java | 45     | Nedostatak komentara za kompleksnije delove koda                           |
| Calculator.java | 50     | Magic values (operatori) nisu izdvojeni u konstante                        |
| Start.java      | 5      | Main metoda sadrži logiku umesto da delegira odgovornost                   |
| Start.java      | 8      | Nema validacije korisničkog unosa                                          |
| Start.java      | 12     | Nema obrade grešaka pri unosu                                              |
| Start.java      | 15     | Loša separacija UI i poslovne logike                                       |
