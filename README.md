# laya-free-backup — Laya v1.10.5 (Apache-2.0)

Free backup of **Laya v1.10.5**, pinned before any future paid change.

- Original: https://github.com/aayushch/laya (tag `v1.10.5`, commit `e8c5426`, 07 Oct 2026)
- License: Apache-2.0 — see `LICENSE-laya-Apache2.0.txt`. This version stays free forever under Apache-2.0.
- Starred upstream for tracking.

## Files

```
installers/Laya_1.10.5_x64-setup.exe  (29,821,240 bytes)
installers/Laya_1.10.5_x64_en-US.msi  (33,800,899 bytes)
source/laya-1.10.5-source.zip         (55,094,448 bytes)
```

## SHA256

```
Laya_1.10.5_x64-setup.exe: BC5577AEADCEEA558BB395A0452D9EE2E4B98783A29CD02EE733E1DE7BB01B01
Laya_1.10.5_x64_en-US.msi: 0DFAB9AAFDA4B58067761B0602DDB6454D6BA01AD08A66F4B50CFCD9E0E29ACD
laya-1.10.5-source.zip:    9BB6409AB57DAFC396E8E9F6499C40791537CE47369A73B5FAA412C45045A701
```

Verify:
```powershell
Get-FileHash -Algorithm SHA256 installers\Laya_1.10.5_x64-setup.exe
Get-FileHash -Algorithm SHA256 installers\Laya_1.10.5_x64_en-US.msi
Get-FileHash -Algorithm SHA256 source\laya-1.10.5-source.zip
```

## Install (Windows, no admin)

```powershell
msiexec /i "installers\Laya_1.10.5_x64_en-US.msi" MSIINSTALLPERUSER=1 ALLUSERS=2 /qn /norestart
# -> %LOCALAPPDATA%\Programs\Laya\laya-app.exe
```

Original links:
- https://github.com/aayushch/laya/releases/download/v1.10.5/Laya_1.10.5_x64-setup.exe
- https://github.com/aayushch/laya/releases/download/v1.10.5/Laya_1.10.5_x64_en-US.msi
- https://github.com/aayushch/laya/archive/refs/tags/v1.10.5.zip
