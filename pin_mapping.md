# Pin Mapping - Col to GPIO

### Columns

```
10_KB_FN    P1.11
11_KB_Ctrl  P0.26
12_KB_SFTL  P0.06
13_KB_SFTR  P0.05
14_COL1	    P0.08
15_COL2	    P1.09
16_COL3	    P0.04
17_COL4	    P1.09
18_KB_WinL  P0.15
19_KB_WinR  P0.07
20_COL5	    P0.17
21_COL6	    P0.20
22_COL7	    P0.13
23_COL8	    P0.22
27_COL9	    P1.02
28_COL10    P1.06
```

### Rows

```
2_ROW1	P0.30
3_ROW2	P0.31
4_ROW3	P0.29
5_ROW4	P0.02
6_ROW5	P1.13
7_ROW6	P0.28
8_ROW7	P0.03
9_ROW8  P1.10
```

# Matrix to Keys

|     | C0  | C1   | C2      | C3      | C4  | C5  | C6  | C7   | C8    | C9    | C10 | C11   | C12     | C13        | C14        | c15         |
| --- | --- | ---- | ------- | ------- | --- | --- | --- | ---- | ----- | ----- | --- | ----- | ------- | ---------- | ---------- | ----------- |
| R0  | FN  | Ctrl | Shift_L | Alt_L   | esc | 1   | Tab | Caps | WIN_R | WIN_L | `   | Space | ←       | ↑          | ↓         | →           |
| R1  |     |      |         |         | F1  | 2   | Q   | A    |       |       | Z   | End   | Pg_down | Pg_up      | Home       | Pause       |
| R2  |     |      |         |         | F2  | 3   | W   | S    |       |       | X   | Menu  | Enter   |            |            | Prt_Sc      |
| R3  |     |      |         |         | F3  | 4   | E   | D    |       |       | C   | Ins   | \\      | ]          | Back_space | Num_lock    |
| R4  |     |      |         |         | F4  | 5   | R   | F    |       |       | V   | Del   | '       | [          | =          | Scroll_lock |
| R5  |     |      | Alt_R   | Shift_R | F5  | 6   | T   | G    |       |       | B   | /     | ;       | P          | -          | F10         |
| R6  |     |      |         |         | F6  | 7   | Y   | H    |       |       | N   | .     | L       | O          | 0          | F9          |
| R7  |     |      |         |         | F7  | 8   | U   | J    |       |       | M   | ,     | K       | I          | 9          | F8          |


|      | C0  | C1   | C2      | C3      | C4  | C5  | C6  | C7   | C8    | C9    | C10 | C11   | C12     | C13        | C14        | c15         |
| ---  | --- | ---- | ------- | ------- | --- | --- | --- | ---- | ----- | ----- | --- | ----- | ------- | ---------- | ---------- | ----------- |
| R0  | RC(0,0) | RC(0,1) | RC(0,2) | RC(0,3) | RC(0,4) | RC(0,5) | RC(0,6) | RC(0,7) | RC(0,8) | RC(0,9) | RC(0,10) | RC(0,11) | RC(0,12) | RC(0,13) | RC(0,14) | RC(0,15) |
| R1  |         |         |         |         | RC(1,4) | RC(1,5) | RC(1,6) | RC(1,7) |         |         | RC(1,10) | RC(1,11) | RC(1,12) | RC(1,13) | RC(1,14) | RC(1,15) |
| R2  |         |         |         |         | RC(2,4) | RC(2,5) | RC(2,6) | RC(2,7) |         |         | RC(2,10) | RC(2,11) | RC(2,12) |          |          | RC(2,15) |
| R3  |         |         |         |         | RC(3,4) | RC(3,5) | RC(3,6) | RC(3,7) |         |         | RC(3,10) | RC(3,11) | RC(3,12) | RC(3,13) | RC(3,14) | RC(3,15) |
| R4  |         |         |         |         | RC(4,4) | RC(4,5) | RC(4,6) | RC(4,7) |         |         | RC(4,10) | RC(4,11) | RC(4,12) | RC(4,13) | RC(4,14) | RC(4,15) |
| R5  |         |         | RC(5,2) | RC(5,3) | RC(5,4) | RC(5,5) | RC(5,6) | RC(5,7) |         |         | RC(5,10) | RC(5,11) | RC(5,12) | RC(5,13) | RC(5,14) | RC(5,15) |
| R6  |         |         |         |         | RC(6,4) | RC(6,5) | RC(6,6) | RC(6,7) |         |         | RC(6,10) | RC(6,11) | RC(6,12) | RC(6,13) | RC(6,14) | RC(6,15) |
| R7  |         |         |         |         | RC(7,4) | RC(7,5) | RC(7,6) | RC(7,7) |         |         | RC(7,10) | RC(7,11) | RC(7,12) | RC(7,13) | RC(7,14) | RC(7,15) |

```
&kp ESC  &kp F1  &kp F2  &kp F3  &kp F4  &kp F5  &kp F6  &kp F7  &kp F8  &kp F9  &kp F10  &kp KP_NUM  &kp PSCRN  &kp SLCK  &kp PAUSE_BREAK  
&kp NUMBER_1  &kp NUMBER_2  &kp NUMBER_3  &kp NUMBER_4  &kp NUMBER_5  &kp NUMBER_6  &kp NUMBER_7  &kp NUMBER_8  &kp NUMBER_9  &kp NUMBER_0  &kp MINUS  &kp EQUAL  &kp BSPC  &kp HOME  
&kp TAB  &kp Q  &kp W  &kp E  &kp R  &kp T  &kp Y  &kp U  &kp I  &kp O  &kp P  &kp LBKT  &kp RBKT  &kp BSLH  &kp PG_UP  
&kp CAPS  &kp A  &kp S  &kp D  &kp F  &kp G  &kp H  &kp J  &kp K  &kp L  &kp SEMI  &kp SQT  &kp ENTER  &kp PG_DN  
&kp RSHFT  &kp Z  &kp X  &kp C  &kp V  &kp B  &kp N  &kp M  &kp COMMA  &kp PERIOD  &kp SLASH  &kp LSHFT  &kp UP  &kp END  
&kp LCTRL  &kp GLOBE  &kp LWIN  &kp LEFT_ALT  &kp GRAVE  &kp SPACE  &kp RIGHT_ALT  &kp RWIN  &to 1  &kp INS  &kp DEL  &kp LEFT  &kp DOWN  &kp RIGHT
```

# Mapped Matrix

```
RC(0,4)  RC(1,4)  RC(2,4)  RC(3,4)  RC(4,4)  RC(5,4)  RC(6,4)  RC(7,4)  RC(7,15)  RC(6,15)  RC(5,15)  RC(3,15)  RC(2,15)  RC(4,15)  RC(1,15)
RC(0,5)  RC(1,5)  RC(2,5)  RC(3,5)  RC(4,5)  RC(5,5)  RC(6,5)  RC(7,5)  RC(7,14)  RC(6,14)  RC(5,14)  RC(4,14)  RC(3,14)  RC(1,14)
RC(0,6)  RC(1,6)  RC(2,6)  RC(3,6)  RC(4,6)  RC(5,6)  RC(6,6)  RC(7,6)  RC(7,13)  RC(6,13)  RC(5,13)  RC(4,13)  RC(3,13)  RC(3,12)  RC(1,13)
RC(0,7)  RC(1,7)  RC(2,7)  RC(3,7)  RC(4,7)  RC(5,7)  RC(6,7)  RC(7,7)  RC(7,12)  RC(6,12)  RC(5,12)  RC(4,12)  RC(2,12)  RC(1,12)
RC(5,3)  RC(1,10)  RC(2,10)  RC(3,10)  RC(4,10)  RC(5,10)  RC(6,10)  RC(7,10)  RC(7,11)  RC(6,11)  RC(5,11)  RC(0,2)  RC(0,13)  RC(1,11)
RC(0,1)  RC(0,0)  RC(0,9)  RC(0,3)  RC(0,10)  RC(0,11)  RC(5,2)  RC(0,8)  RC(2,11)  RC(3,11)  RC(4,11)  RC(0,12)  RC(0,14)  RC(0,15)
```
