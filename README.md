# Ex-11 -Elliptic-curve-cryptography
## AIM:
The implementation of Elliptic Curve Cryptography (ECC) aims to provide strong security with smaller key sizes, enhancing efficiency in encryption, digital signatures, and key exchange.
## ALGORITHM:
Step 1: Alice and Bob agree on a public elliptic curve and a base point 𝐺 G. 
Step 2: Alice chooses a private key 𝑑 𝐴 d A ​ and computes her public key 𝑃 𝐴 = 𝑑 𝐴 ⋅ 𝐺 P A ​ =d A ​ ⋅G. 
Step 3: Bob chooses a private key 𝑑 𝐵 d B ​ and computes his public key 𝑃 𝐵 = 𝑑 𝐵 ⋅ 𝐺 P B ​ =d B ​ ⋅G. 
Step 4: Alice computes the shared secret 𝑆 𝐴 = 𝑑 𝐴 ⋅ 𝑃 𝐵 S A ​ =d A ​ ⋅P B ​ . 
Step 5: Bob computes the shared secret 𝑆 𝐵 = 𝑑 𝐵 ⋅ 𝑃 𝐴 S B ​ =d B ​ ⋅P A ​ (both 𝑆 𝐴 S A ​ and 𝑆 𝐵 S B ​ are equal).
## PROGRAM:
```


```
