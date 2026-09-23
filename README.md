# Personal Writeups

Write-ups from CTF competitions, covering pwn, crypto, reversing, misc, and
OSINT/forensics challenges.

| Writeup | Category | Competition | Summary |
|---|---|---|---|
| [Miami](Miami_Writeup.pdf) | Pwn | SunshineCTF 2025 | Classic stack buffer overflow via unsafe `gets()`; offset found with a brute-force overwrite script using `pwntools`. |
| [Rocommunications](Rocommunications_writeup.pdf) | OSINT / Forensics | SunshineCTF 2025 | Traced a Roblox shirt asset to its decal by pulling the asset ID and hitting Roblox's asset-delivery API directly. |
| [Tribble with my skin](Tribble_with_my_skin_writeup.pdf) | OSINT / Forensics | SunshineCTF 2025 | Identified a Minecraft account's UUID and pulled skin history from a third-party archive to recover a flag hidden in the texture. |
| [Guessy](Guessy_writeup.pdf) | Crypto | FortID 2025 | Extracted a secret bit-by-bit from a Paillier homomorphic-encryption oracle using a zero-knowledge, base-3 trit-extraction attack. |
| [Intro Rev](REV_Intro_writeup.pdf) | FortID 2025 | [competition — confirm] | Located and decoded an encrypted string embedded in a binary using Binary Ninja. |
| [OSINT Exam](OSINT_Exam_writeup.pdf) | OSINT | GreyCat 2025 | Six-part OSINT exam identifying locations from photos; 8th solve overall. |
| [Misc A & B](Misc_A_and_B_writeup.pdf) | Misc / Reversing | Google CTF 2025 | Exploited a camera-boundary bug in a Rust-based Sega-Genesis-style game to sequence-break past an obstacle. **Co-authored with Dimitris Tsiplakis** — see below. |

## A note on Misc A & B

This write-up covers both halves of a two-part challenge, solved
independently by two people. The "メガ A" section documents Dimitris
Tsiplakis's solve; my own solve is the second "メガ A" section in the same
document. If you use this in an interview context, be clear about which part
is yours.

## About these

All write-ups are from CTF competitions I've participated in with team
MaaSec. Dates and exact competition names for a few entries above still need
confirming — fill those in before sharing this externally.
