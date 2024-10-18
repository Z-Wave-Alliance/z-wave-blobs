# ZIPTRANSPORT

## Files

  1. z-wave-tools-core/ZipTransport/osx/libziptrans64.dylib
  2. z-wave-tools-core/ZipTransport/win/ziptrans64.dll
  3. z-wave-tools-core/ZipTransport/win/ziptrans32.dll
  4. z-wave-tools-core/ZipTransport/linux/libziptrans64.so
  5. z-wave-tools-core/ZipTransport/arm/libziptrans32.so

## Checksum-Sha256

>NOTE: The checksums are generated from the Files in the same order as listed above.

  1. 0765a393b3397e678cd81a75cbda37825dd74541165538a5e80a92ca7b520247
  2. 43cee4231f41bb0cce7ecc7bc5fdabbfedea89d55d3d123351c35f0b1542e86d
  3. 5b733612e5d1a1d927c667718b912c0c6a09b79de263d70474ee6f57c14d1d6a
  4. d70f2bb9b046cbd6575037fee2a7bd0b1193eea5594bbdad85a5a225ddbff53e
  5. f841f09b7deaa05bce4885794ac7caa85c02421a2ceb3122c4f2c1cba2e80840

## Description

The 'ziptrans' library is used to allow connection between 
application clients and server (DTLS client).

It is a dependency from dll to end-application through:

- DtlsClient for ZipApplication (part of Z-Wave Core libs) used by
  Dtls1ClientTransportClient:
- ZipService in the ZATS - functions provider for TCs implementation
- ZipControllerSession (UnsolicitedClient) in the PCC - functions
  provider for UI Commands (MVVM) implementation.

For the record windows dll were previously distributed via
simplicity-studio in PCC bundle
("Program Files (x86)/Silicon Labs/Z-Wave PC Controller 5/ziptrans*.dll").

This library is linked with the following opensource libraries (under
different permissive licenses):

- https://github.com/openssl/openssl/releases/tag/OpenSSL_1_0_2u
- https://github.com/chriskohlhoff/asio/releases/tag/asio-1-12-2

SiliconLabs has the ZipTransport sources to rebuild ziptrans dlls
(zw-sqa-tools/browse/Tools/ZipTransport).

## Tracking

- Bug-ZWaveAlliance: https://github.com/Z-Wave-Alliance/z-wave-blobs/issues/9
- Bug-SiliconLabs: ZOS-95
- Origin: https://www.silabs.com/documents/login/software/SimplicityStudio-5.iso
- Origin: SiliconLabs:zw-sqa-tools:open-source-contribution-start-4-g6a6994640
- Forwarded: https://github.com/Z-Wave-Alliance/z-wave-blobs/pull/15
- Bug-ZWaveAlliance: https://github.com/Z-Wave-Alliance/z-wave-tools-core/issues/5
- Bug-ZwaveAlliance: https://github.com/Z-Wave-Alliance/z-wave-pc-controller/issues/8

## License

SPDX-License-Identifier: BSD-3-Clause

SPDX-FileCopyrightText: Silicon Laboratories Inc. https://www.silabs.com
