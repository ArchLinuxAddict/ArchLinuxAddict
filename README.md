<div align="center">

# Eliza Pears

**Reverse Engineer · Malware Analyst · Cyber Enthusiast**

[![Arch Linux](https://img.shields.io/badge/Arch_Linux-1793D1?style=flat-square&logo=arch-linux&logoColor=white)](#)
[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](#)
[![Ghidra](https://img.shields.io/badge/Ghidra-FF6A00?style=flat-square)](#)
[![Frida](https://img.shields.io/badge/Frida-FF6A00?style=flat-square)](#)
[![YARA](https://img.shields.io/badge/YARA-6A1B9A?style=flat-square)](#)

</div>

I am a professional reverse engineer and cyber security enthusiast. I take apart obfuscated Android and native code, analyze malware end to end, and turn the findings into reproducible tooling, detection rules, and removal guidance.

Everything published here is independent research: sanitized, evidence-backed, and written for defenders.

## Focus areas

| Area | What I work on |
| --- | --- |
| **Android / native RE** | DEX internals, JNI, ELF analysis, `JNI_OnLoad`, `RegisterNatives`, cross-ABI behavior |
| **Malware analysis** | RATs, stealers, clipboard hijackers - kill chains, IOCs, YARA, removal runbooks |
| **Protection research** | Packers, virtualization-based protection, Dex2C-style native transformation |
| **Tooling** | Analysis pipelines in Python, Ghidra scripting, Frida instrumentation, detection engineering |
| **Platforms** | Arch Linux daily driver; Windows and Android internals as required |

## Featured research

### [Dex2C Recovery Toolkit](https://github.com/ArchLinuxAddict/dex2c-recovery-toolkit)

Evidence-driven toolkit for APKs protected with Dex2C: DEX and native inventory, transformed-method discovery, JNI mapping, native implementation analysis, and deterministic reports with provenance.

### [Shazhudao / Zhuque Android RAT](https://github.com/ArchLinuxAddict/android-shazhudao-rat)

Full technical analysis of a commercial Android RAT distributed through a fake "TikTok Pro" Instagram ad campaign - kill chain, infrastructure, IOCs, YARA rules, and a removal runbook.

### [SckitVMP Research](https://github.com/ArchLinuxAddict/sckit-vmp-research)

Static reconstruction of a packed Android VM: recovered string encoding, method-record layout, and the native execution pipeline behind the VMP container.

### [Windows WebView2 Clipboard Hijacker](https://github.com/ArchLinuxAddict/windows-webview2-clipboard-hijacker)

Field report and detection toolkit for a crypto clipboard hijacker that persists through a WPDShServiceObj COM hijack while masquerading as the Edge WebView2 loader.

## Toolbox

`Python` `C` `C++` `Java` `Kotlin` `Bash` `PowerShell`

`Ghidra` `IDA` `radare2` `Frida` `x64dbg` `Wireshark` `YARA` `Burp Suite`

`Arch Linux` `Android` `Windows`

## Principles

- Public artifacts are sanitized: no third-party binaries, no personal data, no redistributed proprietary code.
- Claims are backed by retained evidence and reproducible steps.
- Detection content is written to be deployed, not just read.
- Disclosure and removal guidance are part of the research, not an afterthought.

---

<sub>Independent security research · FG_Teams · Arch Linux</sub>
