# Mission 5 — Numbers and data

## 1. Task / objective
Convert between decimal, binary and hex, verify with Python, build a converter and explain text encoding.

## 2. Work completed
Did manual conversions, verified them in Python, wrote `number_converter.py`, tested three values, answered encoding questions.

## 3. Commands / tools used
`python3` (interactive mode), `bin()`, `int(x, base)`, `hex()`, `input()`, `int()`, `print()`, `ord()`.

### Task 5.1 - Convert numbers by hand

| Question | Working | Answer |
|---|---|---|
| Decimal 13 → binary | 13÷2=6 rem=1; 6÷2=3 rem=0; 3÷2=1 rem=1; 1÷2=0 rem=1; read upward | 1101 |
| Decimal 25 → binary | 25÷2=12 rem=1; 12÷2=6 rem=0; 6÷2=3 rem=0; 3÷2=1 rem=1; 1÷2=0 rem=1 | 11001 |
| Binary 1010 → decimal | 8+0+2+0 | 10 |
| Binary 1101 → decimal | 8+4+0+1 | 13 |
| Hex A → decimal | A = 10 | 10 |
| Hex 1F → decimal | 1×16 + 15 | 31 |
| Binary 1111 → hex | 1111 = 15 = F | F |

### Task 5.2 — Verify using Python

| Expression | Result | Matches? |
|---|---|---|
| `bin(13)` | `0b1101` | Yes |
| `bin(25)` | `0b11001` | Yes |
| `int('1010', 2)` | 10 | Yes |
| `int('1101', 2)` | 13 | Yes |
| `hex(31)` | `0x1f` | Yes |
| `int('1F', 16)` | 31 | Yes |
| `int('A', 16)` | 10 | Yes |

### Task 5.3 — Build a small number converter
    number = int(input("Enter a decimal number: "))
    print("Binary:", bin(number))
    print("Hexadecimal:", hex(number))

| Test number | Binary output | Hexadecimal output |
|---|---|---|
| 10 | 0b1010 | 0xa |
| 14 | 0b1110 | 0xe |
| 25 | 0b11001 | 0x19 |
| 36 | 0b100100 | 0x24 |

### Task 5.4 — How is text stored?

(Q)  Find the ASCII decimal codes for the uppercase letter A and lowercase letter a.
- ASCII code of `A` = 65, `a` = 97.
(Q)  Explain in one or two sentences why a computer needs an encoding standard to store text.
- Computers store only numbers, so an encoding standard maps each number to a character so all systems agree.
(Q)  Name one example of a character that is not part of basic ASCII.
- A non-ASCII character: `é` (also `₹` or emoji).

## 4. My understanding

I know that `input()` returns text so we need to use `int()` to convert it to an integer. I understood that `bin()`/`hex()` return strings with `0b`/`0x` prefixes showing the base. I cmae to know that UTF-8 covers far more characters than ASCII.

## 5. Difficulties faced

I felt little difficulty in understanding the python number system conversion codes. 

## 6. How I resolved them

I asked my friends and used the help of AI to understand more about python built in funcitons on number system conversions.

## 7. Evidence / files

`number_converter.py`, this README

![alt text](<Mission 5.2.png>)

![alt text](<Mission 5.3.png>)

## 8. Commit details

"Build number converter and practise data representation" — pushed and verified.