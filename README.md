# FaceFusion — AMD port (Radeon 8060S)

One-click Windows installer for FaceFusion, ported from NVIDIA-only to AMD. Free.

## What it does

FaceFusion is a face swapping and enhancement tool. This AMD build uses isolated dependencies and runs on the Radeon 8060S.

## Tested on

- AMD Ryzen AI Max+ 395 with Radeon 8060S (gfx1151)
- BOSGAME M5

Build and hardware verification were carried out on the test machine by our developer team; results are reported from that testing.

## Before you install

**Model weights are NOT included.** On first run, the program downloads its models from their official sources. Nothing is bundled in this installer.

**Hardware check — please read first.** The installer checks your hardware before it installs. This build is made for a machine with an AMD Radeon 8060S (gfx1151) and the AI Video Suite's PyTorch ROCm stack (torch 2.9.1+rocmsdk).

If your machine does not match, the installer shows the specs it found and offers to let you send them to us for review. It then exits without installing anything (exit code 10). Other hardware is not supported by this build.

## Download

Installer: `FaceFusion-AMD-Setup-1.0.0.exe` — 98,962,354 bytes
SHA-256: `df16e3946b646c69d75ed266304ac0b34efa8c95354cb458f14c71ec2b0dbef6`

## We port NVIDIA software to AMD

Hi I'm Hal ports AI software that was made for NVIDIA only, so it runs on AMD hardware.

Got a program you'd like to see ported? Suggest it. And if your AMD machine isn't on our tested list, you can offer your specs for testing through our compatibility program.

Contact us at https://hiimhal.com

## Licence and credit

**Licence — please read carefully:**
- The FaceFusion application is licensed under **OpenRAIL-AS**.
- The HyperSwap models are licensed under **ResearchRAIL** (research use).
- The ArcFace models are **non-commercial** only.
- These terms come from the upstream project and its model authors. This release does not grant any commercial rights in the models, and the model weights are not redistributed here — they are fetched from the official sources by the program itself on first run.

Upstream project: https://github.com/facefusion/facefusion — credit to the FaceFusion authors. This port is not affiliated with or endorsed by the upstream project.

Ported by a developer from Ontario.
Home and full catalogue: https://hiimhal.com
Support: hello@hiimhal.com
