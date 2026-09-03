# Arcane VM

## Description

A multi-stage boot2root machine inspired by the **Arcane** universe (Netflix / League
of Legends) and built for [HackMyVM](https://hackmyvm.eu/) in 2025.

The machine mixes web exploitation, lateral movement between users, and
privilege escalation.

## Difficulty

**Medium**

## Technical specs

| Parameter | Value |
|---|---|
| Guest OS | Ubuntu (64-bit) |
| CPU | 1 vCPU |
| RAM | 4096 MB |
| Disk | ~25 GB |
| Network | Bridged (DHCP) |
| Format | .ova (VirtualBox) |

## Topics covered

<details>
<summary>Click to expand (CONTAINS SPOILERS)</summary>

- Anonymous FTP enumeration 
- Steganography
- Insecure file upload — blacklist bypass
- Sudo misconfiguration + arbitrary file read
- Dictionary attack
- SUID binary abuse (GTFOBins-style)
- Group membership abuse
- Cron job hijacking
- Symlink trick
- A few deliberate red herrings along the way

</details>

## How to play

1. Import the `.ova` into VirtualBox.
2. Boot it in Bridged mode — it will grab an IP via DHCP on your local network.
3. Start with recon and go from there.

[Play on HackMyVM](https://hackmyvm.eu/machines/machine.php?vm=Arcane).

[Download the VM directly from Mega](https://mega.nz/file/zt1G0QqD#BOPS6BPkqah9Fiyl0uU03apdwQGzggScyCNPMNOgNFM).
