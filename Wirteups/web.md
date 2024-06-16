## Robots
<hr>

IP: 172.212.85.131

I vistied the page of the ip address

![image](https://github.com/shayol33/cybCTF/blob/main/Aessts/robots.png)

I visited http://172.212.85.131/robots.txt and the flag was there
```
The robots.txt file is a standard used by websites to communicate with web crawlers and spiders, typically those operated by search engines like Google, Bing, and Yahoo. It is a simple text file placed at the root of a website that instructs web crawlers on how to crawl and index pages on that site.
```

![image](https://github.com/shayol33/cybCTF/blob/main/Aessts/robots1.png)

```Flag:cybCTF{r0b0t5_r0b0t5_r0b0t5}```

## LFI
<hr>

IP: 20.124.85.189

I visited the page and notied that i was supposed to navigate to another directory "/lfi"

![image](https://github.com/shayol33/cybCTF/blob/main/Aessts/lfi.png)

I navigated to the lfi directory and ?page parameter and noticed that it was requesting home.php

The url takes a fileame parameter

![image](https://github.com/shayol33/cybCTF/blob/main/Aessts/lfi-1.png)
