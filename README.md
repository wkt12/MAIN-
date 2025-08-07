███████╗██╗██████╗  ██████╗ ███████╗██╗  ██╗██╗██╗     ██╗     
██╔════╝██║██╔══██╗██╔════╝ ██╔════╝██║ ██╔╝██║██║     ██║     
█████╗  ██║██████╔╝██║  ███╗█████╗  █████╔╝ ██║██║     ██║     
██╔══╝  ██║██╔═══╝ ██║   ██║██╔══╝  ██╔═██╗ ██║██║     ██║     
██║     ██║██║     ╚██████╔╝███████╗██║  ██╗██║███████╗███████╗
╚═╝     ╚═╝╚═╝      ╚═════╝ ╚══════╝╚═╝  ╚═╝╚═╝╚══════╝╚══════╝



# Fido2KillDroid 🔐💣

**Insert. Tap. Vanish. Your data obeys.**

A stealth self-destruct protocol for Android and Termux, powered by FIDO2 security keys and biometric triggers. Compresses the filesystem into an encrypted archive, wipes original data, and exits silently.

## Features
- FIDO2 key challenge + touch listener
- AES-encrypted `.7z` vaults
- Full filesystem compression (`/sdcard`, `/data`, `/system`, `/vendor`)
- Trigger log hidden in `.trigger_log.txt`
- Optional biometric/fingerprint integration



Fido2KillDroid


 is a secure vault destruction protocol triggered by a FIDO2 device tap. It combines rapid encryption, compression, and secure deletion of sensitive vault contents. Designed for scenarios needing fast, authenticated data obliteration, it leverages hardware-backed security and robust cryptography.



Use this image for touchscreen-triggered vault destruction or as a visual “panic” button in your security workflows.

<img width="1024" height="1024" alt="1000041603" src="https://github.com/user-attachments/assets/ff117254-6731-4794-aeb0-709c3c90ef79" />

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Status](https://img.shields.io/badge/status-Active-success)
![Tech](https://img.shields.io/badge/python)


#!/bin/bash
echo "Self-destruct image downloaded as self_destruct.svg"

```
## Self-Destruct Touch Image

![Self Destruct](./self_destruct.svg)

Instant download for any device:
```bash
bash download_self_destruct_img.sh
```
```



Features

AES Encryption: All vault data is encrypted using a strong, reusable AES engine.

FIDO2 Trigger: Tap your registered FIDO2 device to initiate the destruction protocol.

Compression + Encryption: Archives vault content before secure deletion.

Audit Logging: Detailed execution history is kept in.trigger_log.txt.

Backup Snapshots: Encrypted archive snapshots for recovery.

Zero Data Residue: Secure deletion ensures no recoverable traces.

Usage

1. Connect FIDO2 Device: Ensure your FIDO2 device is recognized by your system.

2. Configure Vault: Place files you wish to protect in the vault directory.

3. Run Protocol: python fido_trigger.py

On FIDO2 tap, the protocol compresses, encrypts, and destroys vault contents.

Encrypted archive snapshot is saved in backup/as vault_<timestamp>.7z.enc.

Execution history is appended to logs/.trigger_log.txt


![Status] <(https://img.shields.io/badge/status-Active-success)>
![Tech] <(https://img.shields.io/badge/python-3.11-blue.svg)>
