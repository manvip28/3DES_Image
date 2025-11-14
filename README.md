# 3DES Image Encryption

A simple Jupyter Notebook project demonstrating Triple DES (3DES) encryption and decryption on images.

## Overview

This project applies the Triple DES cryptographic algorithm to encode and decode image files. It provides a clear walkthrough of how 3DES transforms image data and restores it back to its original state.

## Features

* Encrypt images using 3DES with a secret key and initialization vector (IV)
* Decrypt encrypted image data back to its original form
* Step-by-step execution within a Jupyter Notebook
* Great for understanding symmetric encryption on binary data

## Tech Stack

* Python 3.x
* Jupyter Notebook
* PyCryptodome
* Pillow (PIL) or OpenCV

## Installation

Clone the repository:

```bash
git clone https://github.com/manvip28/3DES_Image.git
cd 3DES_Image
```

Install dependencies:

```bash
pip install pycryptodome pillow
```

## Usage

Open the notebook:

```bash
jupyter notebook 3DES_Encod.ipynb
```

Follow the notebook to:

1. Load an image
2. Provide secret key and IV
3. Run the 3DES encryption
4. Decrypt and verify the result

## Why this Project

This project helps learners understand how block ciphers like 3DES operate on binary image data and visualize encryption effects.


## License

MIT License (or specify your preferred license).
