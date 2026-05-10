# UFE: Passive Ultrasonic Facial Expression Recognition

This repository accompanies the paper:

**"UFE: Passive Ultrasonic Sensing for Facial Expression Recognition on Smartphones"**

## Overview

UFE is a passive and privacy-preserving facial expression recognition framework based on smartphone ultrasonic sensing.  
It leverages Multi-Region Acoustic Reflection Modeling (MRARM) and the Expression-Acoustic Transformer (EA-Former) to extract subtle facial expression-related acoustic variations and map them to predefined facial expression categories.

> Due to privacy and institutional restrictions, the full dataset and complete training pipeline are not publicly released.

## Repository Scope

This repository provides:

- System architecture and pipeline diagrams (`docs/`)
- Example signal preprocessing scripts (`preprocessing/`)
- ERAM feature construction examples (`preprocessing/`)
- EA-Former model structure (`models/`)
- Demo inference scripts (`demo/`)

## Installation

```bash
git clone https://github.com/<your-username>/UFE.git
cd UFE
pip install -r requirements.txt
