# AntiDot Android Banking Trojan

> **Coming soon.** This repo is being prepared; the code, detections and report land here as soon as they are finished.

Static analysis of an AntiDot Android banker sample: the native-backed packer, Accessibility and overlay abuse, OTP theft through the default SMS role, and what banks can detect.

- Write-up (coming soon): https://artfuldodger10.github.io/posts/AntiDot-Android-Banker-Analysis/
- Case file in my portfolio: https://artfuldodger10.github.io/portfolio/#/case/antidot

## What it will cover

- Native-backed packer: XOR-decoded asset manifest, per-ABI native library, hidden DEX
- Accessibility services, overlays, the default SMS role, call screening, screen capture
- C2 and target-app list, mapped to ATT&CK for Mobile

## Planned contents

| Path | What it will hold |
|---|---|
| `reports/` | The full report |
| `tools/` | String decryption (Python) and Frida scripts |
| `detections/` | Detection ideas and rules |
| `iocs/` | IOCs |
| `attack/` | ATT&CK for Mobile layer |

---
Nader Ayman · [Portfolio](https://artfuldodger10.github.io/portfolio/) · [Blog](https://artfuldodger10.github.io/) · [GitHub](https://github.com/ArtfulDodger10)
