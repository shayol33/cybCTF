## cybCTF

<hr>

I Downloade the file and extracted it. 

To extract a .tar.gz file
```
tar -xzf filename.tar.gz
```

After extracting the file, there was so much file in it.

![image](https://github.com/shayol33/cybCTF/blob/main/Aessts/rev.png)

i search for the flag pattern in the directory using Grep

```
grep -r "cybCTF{" .
```

The challange has 3 flags in it

![image](https://github.com/shayol33/cybCTF/blob/main/Aessts/rev2.png)

```
FLag 1: cybCTF{80NU5_4PK}
Flag 2: cybCTF{84CKUP_0N_4PK_H4H4H4}
```

To  get the third flag flag, i ran ```exiftool``` on the image file 

![image](https://github.com/shayol33/cybCTF/blob/main/Aessts/rev3.png)

``` Flag3: cybCTF{wh0_run_ex1ft00l_0n_my_1m4g3} ```

