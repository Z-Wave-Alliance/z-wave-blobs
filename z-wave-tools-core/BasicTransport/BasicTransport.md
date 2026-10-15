# ZIPTRANSPORT

## Files

  1. z-wave-tools-core/BasicTransport/linux/libbasictrans64.so
  2. z-wave-tools-core/BasicTransport/arm/libbasictrans32.so
  3. z-wave-tools-core/BasicTransport/osx/libbasictrans64.dylib
  
## Checksum-Sha256

>NOTE: The checksums are generated from the Files in the same order as listed above.

  1. baf86e15d483cc205f6977f0b611b87632c863eda89afa1d15a8b4696fd14968
  2. ce5f173c79c5d721a44c38ddc74d3b26d434e7211cb0c021f3de4bab2ba851b4
  3. 3458cad874cccb92dca6537d864c6e0ec16295f0809fe6acf059dd48939a5e44

## Description

The 'basictrans' library is used to allow connection between 
NCP and tools.

It provides support with SerialPort connection for non-windows implementations.

Functions are imported by z-wave-tools-core NativeSerialProviderUnix.cs UzbProviderUnix.cs

This library is linked with the following opensource libraries
(under different licenses):

- https://github.com/libusb/libusb/tree/v1.0.22/
- https://github.com/chriskohlhoff/asio/releases/tag/asio-1-12-2

## Exit plan

SiliconLabs has the BasicTransport sources to rebuild blob,
but static linking is not desirable.
When sources are available *dynamic linking* will be preferred
to allow proper distribution and comply mentioned licenses.

## Tracking

- Bug-ZWaveAlliance: https://github.com/Z-Wave-Alliance/z-wave-blobs/issues/10
- Bug-SiliconLabs: ZOS-96
- Origin: https://www.silabs.com/documents/login/software/SimplicityStudio-5.iso
- Origin: SiliconLabs:zw-sqa-tools:open-source-contribution-start-4-g6a6994640
- Forwarded: https://github.com/Z-Wave-Alliance/z-wave-blobs/pull/14
- Bug-ZWaveAlliance: https://github.com/Z-Wave-Alliance/ede/issues/1
- Bug-ZWaveAlliance: https://github.com/Z-Wave-Alliance/z-wave-tools-core/issues/5

## License

SPDX-License-Identifier: BSD-3-Clause
SPDX-FileCopyrightText: Silicon Laboratories Inc. <https://www.silabs.com>
