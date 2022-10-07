# mp4decrypt-aesni
Accelerate mp4decrypt with AES-NI

---

This patch, adapted from [a Gist snippet](https://gist.github.com/acapola/d5b940da024080dfaf5f), patches [Bento4](https://github.com/axiomatic-systems/Bento4)'s [AES implementation](https://github.com/axiomatic-systems/Bento4/blob/master/Source/C%2B%2B/Crypto/Ap4AesBlockCipher.cpp) to use the AES-NI instruction set, thus accelerating MP4 decryption.
