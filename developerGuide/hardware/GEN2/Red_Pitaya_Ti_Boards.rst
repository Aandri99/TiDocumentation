.. _top_stemlab_ti_boards:

###############################
STEMlab TI Boards
###############################

.. note::

   **This page is under construction.** All relevant information for the STEMlab TI series will be finalized upon official release.

Overview
--------

Two versions of the board will be available:

- **STEMlab 125-14 TI**, featuring the TI ADC3664 (14-bit, 125 MSps) with high SNR, low power, low latency, and on-chip digital filtering and digital downconversion (DDC).
- **STEMlab 65-16 TI**, built around the TI ADC3663 dual-channel 16-bit, 65 MSps ADC, optimized for low noise and ultra-low power operation.

Both models also include:

- **TI DAC2904Y**, a 14-bit, 125 MSps dual-channel digital-to-analog converter
- **TI LMK03318**, a programmable ultra-low jitter clock generator
- **2 RF inputs** (125 MSps 14-bit or 62.5 MSps 16-bit, DC coupled)
- **2 RF outputs** (125 MSps, 14 bit)
- **Xilinx Zynq‑7020 FPGA** with dual-core ARM Cortex‑A9 and 1 Gbit Ethernet connectivity

.. contents:: **Index**
    :local:
    :backlinks: none

Pinout
========

.. TODO replace pinout diagram for each model

.. figure:: ../../../../_images/Red_Pitaya_pinout.jpg
   :alt: Red Pitaya pinout
   :width: 700

Technical specifications
==========================

Specifications vary by model; see individual model pages below:

.. toctree::
    :hidden:

    stemlab_125-14_TI
    stemlab_65-16_TI

Each model page covers:

- **Basic** (processor, FPGA, memory, power)
- **Connectivity** (Ethernet, USB, Wi‑Fi)
- **RF inputs** (channels, sample rate, resolution, bandwidth)
- **RF outputs** (channels, sample rate, resolution, jitter)
- **Extension connectors** (GPIOs, analog I/O, external clock)
- **Synchronisation** (trigger, daisy‑chain)
- **Boot options** (SD, QSPI, eMMC)

Schematics
============

.. TODO add development schematics for each model

Mechanical Specifications and 3D Models
========================================

.. TODO add mechanical drawings and 3D models

Components
===========

Common component highlights across the TI series:

- **ADC**: TI ADC3664 (14 bit, 125 MSps) or TI ADC3663 (16 bit, 65 MSps)
- **DAC**: TI DAC2904Y (14 bit, 125 MSps)
- **Clock generator**: TI LMK03318 (ultra-low jitter)
- **FPGA**: Xilinx Zynq‑7020 with dual-core ARM Cortex‑A9 and 1 Gbit Ethernet

Power Supply
--------------

- **Voltage:** 5 V via USB-C or barrel jack
- **Current:** up to 3 A

External ADC clock
===================

Models support external LVDS Ext. ADC Clk± via the E2 connector and onboard NB6L72 crosspoint switch for source selection.

Other specifications
====================

Refer to each model’s individual page for complete details. For generic STEMlab comparisons, see the STEMlab 125‑14 comparison table.
