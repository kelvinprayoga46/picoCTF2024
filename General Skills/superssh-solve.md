# **Super SSH**
Sanity check adalah proses pemeriksaan dan validasi awal terhadap input atau data untuk memastikan bahwa input tersebut memenuhi persyaratan dasar atau logika yang diharapkan. Sanity check digunakan untuk memverifikasi apakah input atau data tersebut masuk akal, konsisten, atau valid sebelum melanjutkan ke langkah-langkah atau pemrosesan selanjutnya.
## **Description**
Using a Secure Shell (SSH) is going to be pretty important. 
Can you ssh as ctf-player to titan.picoctf.net at port 60572 to get the flag?
You'll also need the password 1ad5be0d. If asked, accept the fingerprint with yes.
If your device doesn't have a shell, you can use: https://webshell.picoctf.org
If you're not sure what a shell is, check out our Primer: https://primer.picoctf.com/#_the_shell

![ssh](./images/Super%20SSH.PNG)
## **Solution**
- On this challage we only need to do ssh on account that has been provided.
![ssh1](./images/ssh1.PNG)
- And We got flag
```
picoCTF{s3cur3_c0nn3ct10n_8306c99d}
```

