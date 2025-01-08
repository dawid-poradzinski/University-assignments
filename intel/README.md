# Intel Emulator![Polska](https://img.shields.io/badge/Language-Polish-red?style=flat&logo=flag-icon&logoColor=white)![English](https://img.shields.io/badge/Language-English-blue?style=flat&logo=flag-icon&logoColor=white)

## Jak uruchomić aplikację ![Polska](https://img.shields.io/badge/Language-Polish-red?style=flat&logo=flag-icon&logoColor=white)
---
1. Zainstaluj zależności:
   ```sh
   npm install
   ```
2. Uruchom aplikację:
   ```sh
   npm start
   ```
   lub
   ```sh
   npm run build
   ```

## Technologie

Aplikacja została zbudowana przy użyciu następujących technologii:
- **Node.js**: Środowisko uruchomieniowe JavaScript.
- **React**: Biblioteka do budowania interfejsów użytkownika.
- **React Router**: Biblioteka do zarządzania routingiem w aplikacji.
- **Tailwind CSS**: Narzędzie do stylizacji CSS.

## Komendy

Poniżej znajduje się lista wszystkich komend dostępnych w folderze `src/commands`:

1. `Add`
   - **Opis:** Dodaje wartość arg2 do arg1.
   - **Składnia:** `Add arg1 arg2`
   - **Przykład:** `Add AH AL`

2. `And`
   - **Opis:** Porównuje bity arg1 i arg2: jeśli oba bity są 1, wynik to 1; w przeciwnym razie 0.
   - **Składnia:** `And arg1 arg2`
   - **Przykład:** `And AH AL`

3. `Dec`
   - **Opis:** Zmniejsza wartość arg1 o 1.
   - **Składnia:** `Dec arg1`
   - **Przykład:** `Dec AH`

4. `Exch`
   - **Opis:** Zamienia wartości arg1 i arg2.
   - **Składnia:** `Exch arg1 arg2`
   - **Przykład:** `Exch AH AL`

5. `Imul`
   - **Opis:** Mnoży wartość arg1 przez AL, zwracając wynik 16-bitowy na AH i AL. Wartości są traktowane jako liczby bez znaku (-128 - 127).
   - **Składnia:** `Imul arg1`
   - **Przykład:** `Imul AH`

6. `Inc`
   - **Opis:** Zwiększa wartość arg1 o 1.
   - **Składnia:** `Inc arg1`
   - **Przykład:** `Inc AH`

7. `Mov`
   - **Opis:** Kopiuje wartość arg2 do arg1.
   - **Składnia:** `Mov arg1 arg2`
   - **Przykład:** `Mov AH AL`

8. `Mul`
   - **Opis:** Mnoży wartość arg1 przez AL, zwracając wynik 16-bitowy na AH i AL. Wartości są traktowane jako liczby bez znaku (0 - 255).
   - **Składnia:** `Mul arg1`
   - **Przykład:** `Mul AH`

9. `Neg`
   - **Opis:** Konwertuje wartość arg1 z dodatniej na ujemną lub odwrotnie.
   - **Składnia:** `Neg arg1`
   - **Przykład:** `Neg AH`

10. `Not`
    - **Opis:** Neguje bity arg1 z 0 na 1 i odwrotnie.
    - **Składnia:** `Not arg1`
    - **Przykład:** `Not AH`

11. `Or`
    - **Opis:** Porównuje bity arg1 i arg2: jeśli przynajmniej jeden bit jest 1, wynik to 1; w przeciwnym razie 0.
    - **Składnia:** `Or arg1 arg2`
    - **Przykład:** `Or AH AL`

12. `Sub`
    - **Opis:** Odejmuje wartość arg2 od arg1.
    - **Składnia:** `Sub arg1 arg2`
    - **Przykład:** `Sub AH AL`

13. `Xor`
    - **Opis:** Porównuje bity arg1 i arg2: jeśli tylko jeden bit jest 1, wynik to 1; w przeciwnym razie 0.
    - **Składnia:** `Xor arg1 arg2`
    - **Przykład:** `Xor AH AL`


## How to run the application ![English](https://img.shields.io/badge/Language-English-blue?style=flat&logo=flag-icon&logoColor=white)

1. Install dependencies:
   ```sh
   npm install
   ```
2. Run the application:
   ```sh
   npm start
   ```
   or
   ```sh
   npm run build
   ```

## Technologies

The application was built using the following technologies:
- **Node.js**: JavaScript runtime environment.
- **React**: Library for building user interfaces.
- **React Router**: Library for managing routing in the application.
- **Tailwind CSS**: CSS styling tool.

## Commands

Below is a list of all commands available in the `src/commands` folder:

1. `Add`
   - **Description:** Adds the value of arg2 to arg1.
   - **Syntax:** `Add arg1 arg2`
   - **Example:** `Add AH AL`

2. `And`
   - **Description:** Compares the bits of arg1 and arg2: if both bits are 1, the result is 1; otherwise 0.
   - **Syntax:** `And arg1 arg2`
   - **Example:** `And AH AL`

3. `Dec`
   - **Description:** Decreases the value of arg1 by 1.
   - **Syntax:** `Dec arg1`
   - **Example:** `Dec AH`

4. `Exch`
   - **Description:** Swaps the values of arg1 and arg2.
   - **Syntax:** `Exch arg1 arg2`
   - **Example:** `Exch AH AL`

5. `Imul`
   - **Description:** Multiplies the value of arg1 by AL, returning a 16-bit result in AH and AL. Values are treated as signed numbers (-128 to 127).
   - **Syntax:** `Imul arg1`
   - **Example:** `Imul AH`

6. `Inc`
   - **Description:** Increases the value of arg1 by 1.
   - **Syntax:** `Inc arg1`
   - **Example:** `Inc AH`

7. `Mov`
   - **Description:** Copies the value of arg2 to arg1.
   - **Syntax:** `Mov arg1 arg2`
   - **Example:** `Mov AH AL`

8. `Mul`
   - **Description:** Multiplies the value of arg1 by AL, returning a 16-bit result in AH and AL. Values are treated as unsigned numbers (0 to 255).
   - **Syntax:** `Mul arg1`
   - **Example:** `Mul AH`

9. `Neg`
   - **Description:** Converts the value of arg1 from positive to negative or vice versa.
   - **Syntax:** `Neg arg1`
   - **Example:** `Neg AH`

10. `Not`
    - **Description:** Negates the bits of arg1 from 0 to 1 and vice versa.
    - **Syntax:** `Not arg1`
    - **Example:** `Not AH`

11. `Or`
    - **Description:** Compares the bits of arg1 and arg2: if at least one bit is 1, the result is 1; otherwise 0.
    - **Syntax:** `Or arg1 arg2`
    - **Example:** `Or AH AL`

12. `Sub`
    - **Description:** Subtracts the value of arg2 from arg1.
    - **Syntax:** `Sub arg1 arg2`
    - **Example:** `Sub AH AL`

13. `Xor`
    - **Description:** Compares the bits of arg1 and arg2: if only one bit is 1, the result is 1; otherwise 0.
    - **Syntax:** `Xor arg1 arg2`
    - **Example:** `Xor AH AL`
