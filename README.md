# Malware Source Archive

> A reference collection of historical malware source code, preserved for security research and education.

[![Purpose](https://img.shields.io/badge/purpose-research%20%26%20education-blue.svg)](#disclaimer)

## Overview

This repository archives the source code of notable trojans, viruses, worms, and rootkits. The goal is to give researchers, students, and defenders a way to study how real-world malware was designed and how its techniques worked, so that better detections and defenses can be built.

The code here is **inert reference material**. It is published for analysis, not for use.

## Contents

### Worms

#### `lnk virus.txt`

A well-known worm that propagates by creating malicious shortcuts (`.lnk`) on USB drives. Its full source is included as a study of how compactly such a worm was implemented.

Notable characteristics:

- Self-propagation across removable media
- Reporting back to a remote host
- Exfiltration of data to a remote host
- Acceptance of remote commands from its operator
- Suspected origin: USA

## Disclaimer

This material is provided strictly for **educational and defensive security research purposes**. Do **not** compile, deploy, or distribute any of this code against systems you do not own or are not explicitly authorized to test. Doing so may be illegal. The author accepts no liability for misuse. You are solely responsible for complying with all applicable laws.

## Contact

Questions or feedback: [rehan_manzoor@outlook.com](mailto:rehan_manzoor@outlook.com)
