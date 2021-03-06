# vigenere-cipher
A Vigenere Cipher library for CodeIgniter

Intro
=====
Vigenère Cipher is a plain-text form of encryption that uses alphabetical substitution to encrypt text. The Vigenère Cipher uses something called a "*Tabula Recta*", a grid of alphabetic characters where you can shift lines for alphabetic substitution. **The shifting process is done according to a repeating keyword** which serves to make the encryption more complex and more difficult to decrypt.

![Image](https://upload.wikimedia.org/wikipedia/commons/thumb/9/9a/Vigen%C3%A8re_square_shading.svg/500px-Vigen%C3%A8re_square_shading.svg.png "Tabula Recta")

Installation
============
Before you initialize the library, the first thing you must do is copy the **`Vigenere.php`** to your CodeIgniter project **`/application/libraries`** directory. After that you can simply initialize the library on your **Controller**. Put it on the `__construct()` function.

```
function __construct(){ 
  parent::__construct();
  
  $this->load->library('vigenere'); 
}
```
After that, you can simply call the function like example below :
```
// For encrypting the message
$this->vigenere->encrypt('<your message>', '<your key>');

// For decrypting the message
$this->vigenere->decrypt('<your message>', '<your key>');
```

The Developers
--------------
**Ichwanul Fadhli**

GitHub    : [@ichwanulf99](https://github.com/ichwanulf99/)

Instagram : [@ichwa_nf](https://www.instagram.com/ichwa_nf/)

**Dhimas Panjie Herlambang**

GitHub    : [@DhimasPH](https://github.com/DhimasPH/)

Instagram : [@dhimas_herlambang](https://www.instagram.com/dhimas_herlambang/)

Note
----
There might be some update for the improvement some time in the future.

Copyright (c) 2020 Ichwanul Fadhli & Dhimas Panjie Herlambang
