## Cryptography

## 13
Subsituted the alphabets which are found after 13 shifts <br />
The flag is ```picoCTF{not_too_bad_of_a_problem}```

## mod26
Subsituted the alphabets which are found after 13 shifts [In description they gave ROT 13] <br />
The flag is ```picoCTF{next_time_I'll_try_2_rounds_of_rot13_Aphnytiq}```

## Mind your Ps and Qs
We are given a text file consisting of values n , c and e. Using [factordb.com](http://factordb.com/) found the values of p and q. Using these 5 values gave a hex string . On decoding the hex string in a terminal , <br />
```text
bytes.fromhex('7069636f4354467b736d6131315f4e5f6e305f67306f645f34353336393338377d').decode("utf-8")
```
we will recieve the flag for this challenge. <br />
The required flag is ```picoCTF{sma11_N_n0_g0od_45369387}```
