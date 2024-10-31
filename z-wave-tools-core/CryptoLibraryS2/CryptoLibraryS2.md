# CRYPTOLIBRARY S2

## Files

 1. z-wave-tools-core/CryptoLibraryS2/arm/libs2crypto32.so
 2. z-wave-tools-core/CryptoLibraryS2/linux/libs2crypto32.so
 3. z-wave-tools-core/CryptoLibraryS2/linux/libs2crypto64.so
 4. z-wave-tools-core/CryptoLibraryS2/osx/libs2crypto64.dylib
 5. z-wave-tools-core/CryptoLibraryS2/win/s2crypto32.dll
 6. z-wave-tools-core/CryptoLibraryS2/win/s2crypto64.dll

## Checksum-Sha256

>NOTE: The checksums are generated from the Files in the same order as listed above.

 1. 1368c3233a5df791f3e3a633a17190b8aed393f77f28a761bfba8d6bcb150e72
 2. 8f6f673ccbf6b171d0d99d6482d5cf79bcb2efc9150977fe75f4dd281cde1bc9
 3. 91a1459bdc97667f5872b1d09e165f1b81420fd748a0604a5ce44dfacc4ddafc
 4. 3c8b8c749a635fb0bc194dbbaba037d72ee4114e378163fb4aaa6979c69ea27b
 5. 9806b39d85e56d8610aec8c6db2d52a273fd6788a00a8bd0f49463e63c18d487
 6. d68d596a3b0ec2c8c50c8d2267d6b3a6f98c8664fc00af7e106c20dfeaf0f901

Origin: SiliconLabs:zw-libs2:unknown

## Description

This library is created from the libs2 crypto module. The commit where this library is created is unknown.
The source of this library has been shared with the Z-Wave Alliance, but that code can not be compiled for Windows, because
the code needs some modification (eliminate implicit declarations and fix memory leaks). The code can be compiled for every 
platform with CLANG. This library is available in the SimplicityStudio's PC Zniffer and PC Controller.

## Tracking

- Bug-ZWaveAlliance: https://github.com/Z-Wave-Alliance/z-wave-blobs/issues/11
- Bug-SiliconLabs: ZOS-97
- Relate-to: https://github.com/Z-Wave-Alliance/z-wave-tools-core/issues/5
- Relate-to: https://github.com/Z-Wave-Alliance/z-wave-security/issues/7

## License

SPDX-License-Identifier: BSD-3-Clause

SPDX-FileCopyrightText: Silicon Laboratories Inc. https://www.silabs.com