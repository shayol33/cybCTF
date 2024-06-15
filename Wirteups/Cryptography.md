## Esay-13

<hr>

```
*Author:Theory*

something seems Rotten

ploPGS{arkg_gvzr_V'yy_gel_2_ebhaqf_bs_ebg13_Ncualgvd

```

From the name of the challenge, i already knew it was a ROT-13 cipher. So i opened up [cyberchef](https://gchq.github.io/CyberChef/) and pasted the cipher there and added the ROT13 recipie

![image](https://github.com/shayol33/cybCTF/blob/main/Aessts/ROT-13.png)

```Flag:cybCTF{next_time_I'll_try_2_rounds_of_rot13_Aphnytiq}```

## It's Fine

<hr>

```
*Author:Theory*

hveHGQ{1g_e3t1o5}

Just a quick warm-up cipher for everyone. Honestly, I think it's "a fine" cipher.
```

This is a Affine cipher. i copied it and pasted it on an onlie chipher indentifier [decode.fr](https://www.dcode.fr/cipher-identifier) to be sure of what kind of cipher it is.

![image](https://github.com/shayol33/cybCTF/blob/main/Aessts/it's-fine.png)

After checking up on all the suggested cipher, I found out that it was a Affine cipher. so i was correct

I decoded the the cipher using the same tool https://www.dcode.fr/affine-cipher

![image](https://github.com/shayol33/cybCTF/blob/main/Aessts/it's-fine1.png)

```Flag: cybCTF{1t_b3g1n5} ```

## Weird Stuff

<hr>

```
*Author:Theory*

Part 1: 0110001101111001011000100100001101010100010001100111101100110000011011100110010101011111011101000111011100110000010111110110011000110000
Part 2:	165 162 137 145 151 147 150 164 137 163 151 170 164 63 63
Part 3: 6e5f7468317274797477305f733178
Part 4: dHlmMHVyX25vX20wcmV9

Flag is the concatenation of the four decoded parts.
```

The flag is divided into  parts it's encoded differntly using [cyberchef](https://gchq.github.io/CyberChef/). I deoced each part differently and joined everything together.

Part1: From Binary

![image](https://github.com/shayol33/cybCTF/blob/main/Aessts/from-binary.png)

```cybCTF{0ne_tw0_f0```

Part2: From Octal

![image](https://github.com/shayol33/cybCTF/blob/main/Aessts/from%20octal.png)

```ur_eight_sixt33```

Part3: From Hex

![image](https://github.com/shayol33/cybCTF/blob/main/Aessts/from-hex.png)

```n_th1rtytw0_s1x```

Part4: From BAse64

![image](https://github.com/shayol33/cybCTF/blob/main/Aessts/from-base64.png)

```tyf0ur_no_m0re}```

```Flag:cybCTF{0ne_tw0_f0ur_eight_sixt33n_th1rtytw0_s1xtyf0ur_no_m0re}```

