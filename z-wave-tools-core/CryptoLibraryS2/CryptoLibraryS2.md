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
 2. cdde048009419725b734f2a3af53acd0389087fdca2e32e437c907d682e88eb1
 3. ef9e16187261f5f635134b36e50f6136c2f6297b623ba74635bc012bff7452cf
 4. 982c77f1dfb7d32726f43bc87926343fd8393cc57cbd38c60a37e95eb50e98b8
 5. a3a8d8bb8989dcd1c9702da5a13bacd1bf6a6e168a15aa0474fbd1b442bc11cb
 6. 11835d1ffab872d99afd097bfdc6c1bee981ca53d42442f61683b5ff4ee71dc3

Origin:
- arm/libs2crypto32.so: SiliconLabs:zw-libs2:unknown
- all other files: Z-Wave-Alliance:z-wave-stack:fc241df28d8d3d14034046b1d6a26d846759d753 (v26.8.0-30-gfc241df)

## Description

This library is created from the libs2 crypto module.

The Linux (32/64-bit), macOS (universal x86_64/arm64) and Windows (32/64-bit) libraries are built in CI from
the libs2 sources in https://github.com/Z-Wave-Alliance/z-wave-stack (`SubTree/libs2`, `-DLIBS2_CRYPTO_SHARED=ON`),
workflow run https://github.com/Z-Wave-Alliance/z-wave-stack/actions/runs/43029245272.
Each of these libraries has a `<library>.buildinfo.txt` file next to it with the source commit, runner,
CMake options, compiler and SHA-256 checksum.

The ARM library has not been rebuilt yet. It was created from an unknown libs2 commit and is the version available in
the SimplicityStudio's PC Zniffer and PC Controller.

## Tracking

- Bug-ZWaveAlliance: https://github.com/Z-Wave-Alliance/z-wave-blobs/issues/11
- Bug-SiliconLabs: ZOS-97
- Relate-to: https://github.com/Z-Wave-Alliance/z-wave-tools-core/issues/5
- Relate-to: https://github.com/Z-Wave-Alliance/z-wave-security/issues/7
- Relate-to: https://github.com/Z-Wave-Alliance/z-wave-stack/pull/1017

## License

SPDX-License-Identifier: BSD-3-Clause
SPDX-FileCopyrightText: Silicon Laboratories Inc. <https://www.silabs.com>