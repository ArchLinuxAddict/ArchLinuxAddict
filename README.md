<div align="center">

<img width="100%" alt="Eliza Pears — reverse engineering, malware analysis, security research" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,45:1f6feb,100:58a6ff&height=200&section=header&text=ELIZA%20PEARS&fontSize=54&fontColor=ffffff&animation=fadeIn&fontAlignY=34&desc=Reverse%20Engineering%20%C2%B7%20Malware%20Analysis%20%C2%B7%20Security%20Research&descAlignY=56&descSize=20" />

<a href="https://github.com/ArchLinuxAddict">
  <img alt="Focus areas" src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=3000&pause=900&color=58A6FF&center=true&vCenter=true&width=780&lines=%3E+whoami+%E2%86%92+reverse+engineer+%2F+malware+analyst;%3E+focus+%E2%86%92+Android+%2F+native+RE+%C2%B7+packers+%2F+VMPs;%3E+build+%E2%86%92+evidence-first+tooling%2C+not+guesses;%3E+platform+%E2%86%92+Arch+Linux+daily+driver" />
</a>

<br/>

<a href="https://github.com/ArchLinuxAddict?tab=followers"><img alt="Followers" src="https://img.shields.io/github/followers/ArchLinuxAddict?label=Followers&style=flat-square&color=1F6FEB&labelColor=0D1117" /></a>
<img alt="Profile views" src="https://komarev.com/ghpvc/?username=ArchLinuxAddict&label=Profile%20views&style=flat-square&color=1F6FEB" />
<img alt="Arch Linux" src="https://img.shields.io/badge/Arch_Linux-daily_driver-1793D1?style=flat-square&logo=arch-linux&logoColor=white" />
<img alt="FG Teams" src="https://img.shields.io/badge/FG_Teams-security_research-6A1B9A?style=flat-square" />

</div>

## `$ whoami`

```yaml
identity:  Eliza Pears  # "Furjack"
role:      reverse engineer · malware analyst
org:       FG_Teams — Security Research
platform:  Arch Linux · Windows · Android
focus:     Android/native RE · packers/VMPs
recovery:  JNI/Dex2C · detection engineering
method:    evidence first — provenance always
```

I take apart obfuscated Android and native code, reconstruct what protection layers hide, and turn the result into reproducible tooling, detection content and removal guidance. Everything published here is independent research: sanitized, evidence-backed and written for defenders.

## Focus areas

| Area | What I work on |
| --- | --- |
| **Android / native RE** | DEX internals, JNI, ELF analysis, `JNI_OnLoad`, `RegisterNatives`, cross-ABI behavior |
| **Protection research** | Packers, virtualization-based protection, Dex2C-style native transformation, detector logic |
| **Malware analysis** | RATs, stealers, clipboard hijackers — kill chains, infrastructure, IOCs, YARA, removal runbooks |
| **Tooling** | Python analysis pipelines, Ghidra scripting, Frida instrumentation, deterministic reports |
| **Detection engineering** | Deployable YARA, IOC packages, canary tests, incident-response scripts |

## Featured research

<table>
<tr>
<td>

### [NEXUS-BI](https://github.com/ArchLinuxAddict/nexus-bi)

Tool-first binary intelligence: Ghidra, JADX and CFR own reconstruction; a compact 16.4M-parameter residual model repairs and ranks what deterministic tools cannot close.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Ghidra](https://img.shields.io/badge/Ghidra-FF6A00?style=flat-square&logo=ghidra&logoColor=white)
![JADX](https://img.shields.io/badge/JADX-1F6FEB?style=flat-square)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)

</td>
</tr>
<tr>
<td>

### [Dex2C Recovery Toolkit](https://github.com/ArchLinuxAddict/dex2c-recovery-toolkit)

Evidence-driven recovery for Dex2C-protected APKs: DEX/ELF inventory, transformed-method discovery, JNI registration mapping, validation and SHA-256 provenance manifests.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![Ghidra](https://img.shields.io/badge/Ghidra-FF6A00?style=flat-square&logo=ghidra&logoColor=white)
![JNI](https://img.shields.io/badge/JNI-6A1B9A?style=flat-square)

</td>
</tr>
<tr>
<td>

### [杀猪刀 / Zhuque Android RAT](https://github.com/ArchLinuxAddict/android-shazhudao-rat)

End-to-end teardown of a commercial Android RAT shipped as a fake "TikTok Pro" APK: kill chain, C2 infrastructure, IOCs, YARA and a removal runbook.

![YARA](https://img.shields.io/badge/YARA-6A1B9A?style=flat-square&logo=yara&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![Threat Intel](https://img.shields.io/badge/Threat_Intel-1F6FEB?style=flat-square)

</td>
</tr>
<tr>
<td>

### [SckitVMP Research](https://github.com/ArchLinuxAddict/sckit-vmp-research)

Static reconstruction of a packed Android VM: XOR/modified-UTF-8 string coding, method-record layout, native dispatch pipeline and 159 mapped opcodes.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Ghidra](https://img.shields.io/badge/Ghidra-FF6A00?style=flat-square&logo=ghidra&logoColor=white)
![Virtualization](https://img.shields.io/badge/Virtualization-6A1B9A?style=flat-square)

</td>
</tr>
<tr>
<td>

### [Windows Clipboard Hijacker](https://github.com/ArchLinuxAddict/windows-webview2-clipboard-hijacker)

Field report on a fake WebView2 DLL persisting through a WPDShServiceObj COM hijack: 43 cracked API hashes, a 23-chain address pool, detection and removal scripts.

![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-0078D6?style=flat-square&logo=windows&logoColor=white)
![Detection](https://img.shields.io/badge/Detection_Engineering-1F6FEB?style=flat-square)

</td>
</tr>
<tr>
<td>

### [Dex2C Recovery Lab](https://github.com/ArchLinuxAddict/dex2c-recovery-lab)

Sanitized methodology and reproducible examples behind the Dex2C toolkit — what works, what does not, and the limits of evidence.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Smali](https://img.shields.io/badge/Smali-6A1B9A?style=flat-square)
![Research](https://img.shields.io/badge/Research-1F6FEB?style=flat-square)

</td>
</tr>
</table>

## Research highlights

- Mapped **159 VM opcodes (116 unique handlers)** and the native dispatch pipeline in the SckitVMP container.
- Cracked **all 43 custom API-hash constants** and recovered the full **23-address / 23-chain** replacement pool in the Windows clipboard hijacker.
- Documented a commercial Android RAT end to end — from Instagram ad to accessibility abuse, WebRTC screen streaming and anti-uninstall — with deployable YARA.
- Raised held-out JNI/Java repair token accuracy from **12.0% to 33.0%** with a compact residual model, while keeping deterministic tool output authoritative.
- Shipped a recovery pipeline that writes **SHA-256 provenance manifests** and states its own limits instead of claiming source recovery.

## Toolbox

<div align="center">

<img alt="Languages and platforms" src="https://skillicons.dev/icons?i=py,c,cpp,java,kotlin,bash,powershell,linux,androidstudio,windows,git,github&theme=dark&perline=12" />

<br/><br/>

**Reverse engineering**

![Ghidra](https://img.shields.io/badge/Ghidra-FF6A00?style=flat-square&logo=ghidra&logoColor=white)
![IDA Pro](https://img.shields.io/badge/IDA_Pro-6A1B9A?style=flat-square)
![radare2](https://img.shields.io/badge/radare2-1F6FEB?style=flat-square)
![Frida](https://img.shields.io/badge/Frida-FF6A00?style=flat-square&logo=frida&logoColor=white)
![x64dbg](https://img.shields.io/badge/x64dbg-6A1B9A?style=flat-square)

**Android**

![JADX](https://img.shields.io/badge/JADX-1F6FEB?style=flat-square)
![apktool](https://img.shields.io/badge/apktool-3DDC84?style=flat-square)
![smali](https://img.shields.io/badge/smali%2Fbaksmali-6A1B9A?style=flat-square)
![ADB](https://img.shields.io/badge/ADB-3DDC84?style=flat-square&logo=android&logoColor=white)
![NDK](https://img.shields.io/badge/Android_NDK-3DDC84?style=flat-square&logo=android&logoColor=white)

**Detection and network**

![YARA](https://img.shields.io/badge/YARA-6A1B9A?style=flat-square&logo=yara&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=flat-square&logo=burpsuite&logoColor=white)

</div>

## GitHub analytics

<div align="center">

<img width="400" alt="GitHub stats" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=ArchLinuxAddict&theme=tokyonight" />
<img width="400" alt="Top languages by repository" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=ArchLinuxAddict&theme=tokyonight" />

<br/>

<img width="400" alt="Commits by hour (UTC)" src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=ArchLinuxAddict&theme=tokyonight&utcOffset=0" />
<img width="400" alt="Top languages by commit" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=ArchLinuxAddict&theme=tokyonight" />

<br/><br/>

<img width="500" alt="Contribution streak" src="https://github-readme-streak-stats.herokuapp.com?user=ArchLinuxAddict&theme=tokyonight&hide_border=true&background=0D1117&stroke=30363D&ring=1F6FEB&fire=58A6FF&currStreakLabel=58A6FF&sideLabels=58A6FF&dates=8B949E" />

</div>

## Principles

- **Sanitized by default** — no third-party binaries, personal data or redistributed proprietary code.
- **Evidence first** — claims carry retained provenance and reproducible steps.
- **Deterministic tools stay authoritative** — models assist reconstruction; they do not get to pretend to be truth.
- **Built to deploy** — detection content, IOCs and removal guidance ship with the research, not as an afterthought.

## Elsewhere

- [RePairip](https://github.com/ArchLinuxAddict/RePairip) — fork for Google 加固 (VMRunner) snapshot dumping and full APK repacking.
- Questions, reproducible artifacts or collaboration: open an issue in the relevant repository.

<br/>

<img width="100%" alt="Independent security research · FG_Teams · Arch Linux" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,45:1f6feb,100:58a6ff&height=120&section=footer&text=Independent%20security%20research%20%C2%B7%20FG_Teams%20%C2%B7%20Arch%20Linux&fontSize=18&fontColor=ffffff&fontAlignY=72" />
