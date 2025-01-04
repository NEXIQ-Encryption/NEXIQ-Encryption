[![python3](https://img.shields.io/badge/python3-v3.6-green?style=for-the-badge&logo=python)](https://www.python.org)


# NEXIQ_Encryption
A Post-Quantum Encryption Algorithm

NEXIQ uses lattice-based cryptography to encrypt and decrypt data. Unlike
other popular public-key cryptosystems, it is resistant to
attacks using Shor's Algorithm and its performance has been
shown to be significantly greater. 

This module shows how
Koblitz encoding from Elliptic Curve Cryptography (ECC)
can be used to convert each character in a dataset to a point on
an elliptic curve. A sum of squares analogy is pitted against
the cantor pairing function to turn the point to a single
number, which is converted to a sequence of coefficients in Z.
A polynomial is then generated for each of these characters.
Then the polynomial is reduced, and then shown that choosing
appropriate parameters for the cryptosystem can make it
highly secure and that the decryption algorithm turns out
taking linear time. Since each character is represented by its
own polynomial, it increases obscurity thereby increasing the
complexity for decryption and thus the security level. 

A form
of data compression has also been implemented and it has
been tested whether data compression and expansion during
the encryption-decryption process results in original data with
no or minimal loss.

# The Research Behind NEXIQ
[![DOI:10.5120/ijca2020920320
](https://zenodo.org/badge/DOI/10.5120/ijca2020920320.svg)](https://doi.org/10.5120/ijca2020920320
)

## Cloning
```bash
$ git clone https://github.com/7enTropy7/NEXIQ_Encryption.git
```

## Dependencies
```bash
$ pip3 install -r requirements.txt
```

## Output

![Screenshot from 2020-02-06 12-43-24](https://user-images.githubusercontent.com/36446402/73914025-5d17c580-48de-11ea-8ae5-b07e0940b306.png)

