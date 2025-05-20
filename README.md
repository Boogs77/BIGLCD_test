# BIGLCD_test
Test for display DS-G160128STBWW (RA6963) inspired by https://github.com/crystalfontz/RA6963

Arduino control lines

```
   ARD      | Port  | Display pin |  Function - 8080 Parallel   |
------------+-------+-------------+-----------------------------+
  5V        |       |     03      |  POWER                      |
  GND	    |       |     02      |  GROUND                     |
 -----------+-------+-------------+-----------------------------+
  D8        | PORTB |     08      |  Chip Enable Signal  (\CE)  |
  D9        | PORTB |     11      |  Reset              (\RST)  |
  D10       | PORTB |     09      |  Command/DATA        (C/D)  |
  D11       | PORTB |     06      |  Data Write          (/WR)  |
  D12       | PORTB |     07      |  Data Read           (/RD)  |
 -----------+-------+-------------+-----------------------------+
 Data Lines
 -----------+-------+-------------+-----------------------------+
  D0        | PORTD |     12      |  LCD_D10 (DB0)              |
  D1        | PORTD |     13      |  LCD_D11 (DB1)              |
  D2        | PORTD |     14      |  LCD_D12 (DB2)              |
  D3        | PORTD |     15      |  LCD_D13 (DB3)              |
  D4        | PORTD |     16      |  LCD_D14 (DB4)              |
  D5        | PORTD |     17      |  LCD_D15 (DB5)              |
  D6        | PORTD |     18      |  LCD_D16 (DB6)              |
  D7        | PORTD |     19      |  LCD_D17 (DB7)              |
 -----------+-------+-------------+-----------------------------+
```
there are three differt codes: "Logo", "Hello, World!" and "screensaver"
