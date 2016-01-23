# ARM Development Board Shootout

## Goals

* Demonstrate capabilities of embedded platforms in a reproducible manner: 
  * CPU Performance 
  * Memory Bandwidth
  * GPU
  * VPU
  * Zero-Copy VPU + GPU

* Rate SoCs on ease of use for development and maintenance
  * Find the Most Recent Fully Functioning Kernel Version (MRFFKR)
  * Document the binary blobs and non-OSS licenses required to make full-use of SoC features

## Vendors, SoC Families, and Boards Covered

* TI 
  * OMAP
    * Beagleboard rev C3 (OMAP3530, PowerVR SGX 530)
    * Beagleboard XM rev B (DM3730, PowerVR SGX 530)
  * AM335x
    * Beaglebone Rev C (AM3358)
* Samsung
  * Exynos
    * Samsung Origen Development Board (Exynos 4412)
    * O-droid U2 (Exynos 4412)
* NXP (Formerly Freescale)
    * i.MX6
      * Cubox i4 Pro (i.MX6)
      * Zealz GK 802 (i.MX6 Quad)
* Broadcom
  * BCM28XX
    * Raspberry Pi (BCM2835)
    * Raspberry Pi 2 (BCM2836)

## Per SoC Model Data Points

* Year SoC introduced
* Year board introduced
* CPU Arch
 * Core Type
 * Process Size
 * Number of Cores
 * Clock Speed 
* GPU Arch
 * Number of Shaders/Cores
 * Clock Speed
* VPU/DSP  

## Per Board Data Points

* Amount of Memory

## Per Board Performance Characteristics

* Benchmark Results (CPU, Memory, Disk) 
* For each of Video Only, GPU, and VPU+GPU
  * Framerate at Maximum Resolution
  * Resolution at Maximum Framerate
  * 30fps or better resolution 
  * 60fps or better resolution
