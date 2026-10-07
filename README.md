# InlämningsuppgiftJava

Ett Java-program som läser in text från kommandoraden rad för rad
tills användaren skriver ordet `stop`.

## Vad programmet gör
När användaren skriver `stop` skrivs följande ut (raden med `stop` räknas inte):
- Antal rader
- Antal tecken
- Antal ord (separerade med blanksteg)
- Det längsta ordet

## Struktur
- `Main` – läser in text från användaren och skriver ut resultatet
- `Counter` – räknar rader, tecken och ord, håller koll på längsta ordet
  och kontrollerar om användaren har skrivit `stop`

## Köra programmet
Öppna projektet i IntelliJ och kör `Main.java`.
Skriv text i konsolen och avsluta med `stop`.

## Tester
JUnit 5-tester finns i `src/test/java/org/example/CounterTest.java`.
Kör dem genom att högerklicka på `CounterTest` och välja **Run**.
