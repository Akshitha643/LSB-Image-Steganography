# LSB-Image-Steganography
Image steganography project in C for securely hiding and extracting secret messages inside BMP images using encoding and decoding techniques.

## Overview
Image Steganography is a technique used to securely hide secret information inside an image without visibly altering the image appearance. This project implements image steganography in C using BMP images for encoding and decoding secret messages.

## Objective
The main objective of this project is to provide secure communication by embedding confidential text messages inside image files and retrieving them when required.

## Features
- Encode secret text inside BMP images
- Decode and extract hidden messages
- Secure message hiding technique
- Command line based implementation
- File handling and image processing in C

## Technologies Used
- C Programming
- File Handling
- Bit Manipulation
- BMP Image Processing
- GCC Compiler / Linux Environment

## Project Structure
```text
├── encode.c
├── decode.c
├── common.h
├── encode.h
├── decode.h
├── secret.txt
├── image.bmp
└── README.md
