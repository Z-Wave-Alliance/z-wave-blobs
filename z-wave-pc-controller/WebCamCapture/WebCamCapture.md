# WEBCAMCAPTURE

## Files

  1. z-wave-pc-controller/WebCamCapture/win/wcvcap32.dll
  2. z-wave-pc-controller/WebCamCapture/win/wcvcap64.dll

## Checksum-Sha256

>NOTE: The checksums are generated from the Files in the same order as listed above.

  1. f05c4d35c4afe70cac4978d19ee304398d380d6542f4a5ebdfb9026ffd7fa68a
  2. 15edd94aadde6c6025ca58b850cffbe98946d7dd1ad9ea94be1e70824c4940b5

## Description

The 'wcvcap' library is used to allow picture capture,
for scanning QR code, this feature is used for Z-Wave SmartStart.

Typically Scan the QR code and add it to the Provision list or use value it as PIN code during S2 bootstrapping.

The Z-Wave reference client pc-controller is using it, and CTT too.

For the record windows dll were previously distributed via
simplicity-studio in PCC bundle
("Program Files (x86)/Silicon Labs/Z-Wave PC Controller 5/wcvcap*.dll").

This library is linked with the following opensource libraries (under
different permissive licenses):

- https://github.com/opencv/opencv/blob/4.2.0/LICENSE
- https://github.com/opencv/opencv/releases/tag/4.2.0


Related requirements:

- recommendation DT:00.31.0006.2 (scan QR no matter how) , RT:00.21.000C.1 (S2 PIN input -optionally for a controller);
- SHOULD's: RT:00.12.0006.1 , (S2): CC:009F.01.00.11.0B9, CC:009F.01.00.12.011

## Exit plan

SiliconLabs sources are lost, it might be easier to consider the following options:

- Drop QR feature and provide alternatives headless implementations (using CLI, envars or file)
- Re-implement exported API (OpenWebCam, CloseWebCam) from OpenCV examples (cv::VideoCapture::VideoCapture).


## Tracking

- Bug-ZWaveAlliance: https://github.com/Z-Wave-Alliance/z-wave-blobs/issues/13
- Bug-SiliconLabs: ZOS-98
- Origin: https://www.silabs.com/documents/login/software/SimplicityStudio-5.iso
- Origin-SilconLabs: https://www.silabs.com/#zw-sqa-tools/open-source-contribution-start-4-g6a6994640
- Forwarded: https://github.com/Z-Wave-Alliance/z-wave-blobs/pull/7
- Bug-ZWaveAlliance: https://github.com/Z-Wave-Alliance/z-wave-pc-controller/issues/8
- Bug-ZwaveAlliance: https://github.com/Z-Wave-Alliance/z-wave-pc-controller/pull/6

## License

Check related licences files next to binaries.

SPDX-License-Identifier: BSD-3-Clause
SPDX-FileCopyrightText: Silicon Laboratories Inc. <https://www.silabs.com>
