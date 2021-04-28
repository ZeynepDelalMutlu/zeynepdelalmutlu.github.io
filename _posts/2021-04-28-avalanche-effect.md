---
title:  "Avalanche Effect"
layout: post
---

Cryptanalysis is a field that tries to solve(to find plaintext or key) any cryptographic system by attacking it. There are lots of methods used by cryptanalists such as 'ciphertext only attacks', 'known plaintext attacks', 'chosen plaintext attacks', 'man-in-the-middle attacks', 'side channel attacks', 'brute force attacks' etc. To prevent such attacks, cyrptography has important principles. "Avalache Effect" is one of these precautions which is used for especially block ciphers, cryptographic hash functions and other cryptographic algorithms.


This effect is based on idea that even tiny changing on plain text or key text should cause changing 50% of the cipher text.

Supposing that, we want to form an opinion about one bit of plaintext or key. To do this, we can change one bit from the plain text or key and observe its effect on cipher text. If we do this many times and interpret them together, statistics of the results can give us a strong opinion of the bits plaintext or key. To prevent this, "avalanche effect" is used  in cyptosystems generally. 

In other words, if we change 1 bit from plaintext, 50% of the ciphertext should be changed. Why 50%? Because, we do not want the attacker can make a comment about the plaintext based on this percentage. 50% means, they got nothing to guess about plaintext or key itself. Thus, they can not put forward an idea about the original bits of the plaintext or key.

The text below is the cryptography course project report which indicates "avalanche effect" of AES Algorithm. All project was coded regarding string-bit conversions. There are not any bit manipulations used for "avalanche effect" calculations. Report has the 

To see the project code, please visit: [https://github.com/ZeynepDelalMutlu/aes_diffusion][github] 



<object data="https://zeynepdelalmutlu.github.io/assets/MutluZeynepDelal_Report_ProjectAESConfusionDiffusion.pdf" type="application/pdf" width="700px" height="700px">
    <embed src="https://zeynepdelalmutlu.github.io/assets/MutluZeynepDelal_Report_ProjectAESConfusionDiffusion.pdf">
        <p>This browser does not support PDFs. Please download the PDF to view it: <a href="https://zeynepdelalmutlu.github.io/assets/MutluZeynepDelal_Report_ProjectAESConfusionDiffusion.pdf">Download PDF</a>.</p>
    </embed>
</object>


[github]: https://github.com/ZeynepDelalMutlu/aes_diffusion/

