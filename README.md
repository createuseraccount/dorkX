# dorkX
Pipe different tools with google dork Scanner 

<p align="left">
  <img width="120" height="120" src="https://static.thenounproject.com/png/3095097-200.png">
</p>

#### Version 1.0

[![Image from Gyazo](https://i.gyazo.com/0e66c4d64bf0df9623c18b6e918309b8.gif)](https://gyazo.com/0e66c4d64bf0df9623c18b6e918309b8)

[![Image from Gyazo](https://i.gyazo.com/44ab7aae9b1c0812474278c120dc8807.gif)](https://gyazo.com/44ab7aae9b1c0812474278c120dc8807)


### Install

`zoid@MSI ~/dorkX> git clone https://github.com/ethicalhackingplayground/dorkX && cd corsX && go build`



### Usage:

**XSS**

`zoid@MSI ~/dorkX> ./dorkX -dorks dorks.txt | dalfox pipe`

`zoid@MSI ~/dorkX> ./dorkX -dork "inurl:index.php?id" | dalfox pipe`

**Cors**

`zoid@MSI ~/dorkX>  ./dorkX -dorks dorks.txt | ./corsX`

`zoid@MSI ~/dorkX> ./dorkX -dork "inurl:index.php?id" | ./corsX`

**CSRF**

`zoid@MSI ~/dorkX>  ./dorkX -dorks dorks.txt | ./csrfX`

`zoid@MSI ~/dorkX> ./dorkX -dork "inurl:index.php?id" | ./csrfX`

**Payload Injection**

`zoid@MSI ~/dorkX>  ./dorkX -dorks dorks.txt | ./zin -pL <payloadList>`

`zoid@MSI ~/dorkX> ./dorkX -dork "inurl:index.php?id" |./zin -p <payload>`


**If you get a bounty please support by buying me a coffee**

<a href="https://www.buymeacoffee.com/krypt0mux" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>

