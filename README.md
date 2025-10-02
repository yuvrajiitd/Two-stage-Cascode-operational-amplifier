# Two-stage-Cascode-operational-amplifier

A high-performance cascode operational amplifier designed using TSMC 0.18μm CMOS technology.

## Project Overview

This repository contains the complete design files for a cascode OPAMP implementation including:
- **LTspice Schematic** (`Draft2Final.asc`) - Main amplifier circuit
- **Custom Components** - CMOS transistor symbols
- **TSMC PDK** - Process design kit for simulation

## Files Description

- `Draft2Final.asc` - Main LTspice schematic for the cascode OPAMP
- `cmosn.asy` - NMOS transistor symbol
- `cmosp.asy` - PMOS transistor symbol  
- `tsmc.lib` - TSMC 0.18μm process technology library

## Prerequisites

- **LTspice XVII** (free download from Analog Devices)
- TSMC 0.18μm process library access

## Installation & Setup

### 1. Library Configuration
Add the following line to your LTspice schematic using SPICE directive:
