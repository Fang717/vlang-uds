# Vlang UDS Implementation

This project provides a lightweight and modular implementation of **UDS (Unified Diagnostic Services, ISO 14229)** in **Vlang**, designed for embedded systems, automotive diagnostics, and tooling.

## 🚗 Overview

UDS is the core protocol used for vehicle ECUs (Engine Control Units) to perform diagnostic functions such as:

- Reading and clearing DTCs (Diagnostic Trouble Codes)
- ECU identification and version reporting
- Security access / unlocking
- Flashing firmware
- Routine control and more

This project offers a native implementation of UDS message handling and transport, written entirely in [Vlang](https://vlang.io).

## 🔧 Features

- ✅ Written in 100% pure Vlang
- ✅ POSIX-compliant design, suitable for integration in Unix tools and scripts
- ✅ Basic UDS service support (e.g. 0x10, 0x11, 0x27, 0x31, 0x34, etc.)
- ✅ Transport layer abstraction (CAN, ISO-TP, etc.)
- ✅ Designed for scripting and CLI integration
- ✅ Compatible with `.vsh` (Vlang Shell) scripts

## 📁 Project Structure


