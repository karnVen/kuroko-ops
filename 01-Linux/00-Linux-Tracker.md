# Phase 1: Linux Fundamentals — Tracker & Study Index

> **Status:** Active  
> **Master Roadmap Link:** `../00-DevOps-Roadmap-Master.md`  
> **Structure:**
> - `01-NetworkChuck/`: Video-by-video synthesized notes (one note per episode, including all deep dives & research).
> - `02-HTB-Academy/`: HackTheBox Academy Linux Fundamentals module notes & labs.

---

## 🤝 The One-Note-Per-Episode Rule
When watching an episode:
- All questions, deep-dive investigations, and experiments triggered during that video are added **directly into that episode's single master note**—no scattered files.

---

## 📂 Stream 1: NetworkChuck Playlist Notes (`01-NetworkChuck/`)

| Ep # | Note Link | Core Topics & Research | Status |
|:---:|:---|:---|:---:|
| **01** | [Ep. 01: Terminal & Navigation](01-NetworkChuck/Ep-01-Terminal-and-Navigation.md) | `pwd`, `ls -la`, `cd`, Absolute vs. Relative Paths, Root Tree (`/`) | ✅ Completed |
| **02** | [Ep. 02: Filesystem Hierarchy & Everything is a File](01-NetworkChuck/Ep-02-Filesystem-Hierarchy.md) | FHS, Root (`/`) vs `/root`, VFS Architecture, 7 POSIX File Types, File Descriptors 0/1/2, Docker Socket Security, `EMFILE` | ✅ Completed |

---

## 📂 Stream 2: HackTheBox Academy (`02-HTB-Academy/`)

| Section | Note Link | Topics | Status |
|:---:|:---|:---|:---:|
| **Index** | [HTB Academy Module 18 Overview](02-HTB-Academy/README.md) | Module 18 Linux Fundamentals Tracker | 🔄 In Progress |

---

## 📋 Phase 1 Core Skills Checklist

- [x] Linux Root Tree & FHS structure (`/`, `/etc`, `/var`, `/home`, `/bin`, `/usr`)
- [x] "Everything is a file" doctrine, VFS, and the 7 POSIX file types
- [x] Basic navigation & discovery: `pwd`, `ls -la`, `cd ~`, `cd ..`, `cd -`
- [ ] File operations: `mkdir -p`, `touch`, `cp -r`, `mv`, `rm -rf`
- [ ] File viewing & searching: `cat`, `less`, `head`, `tail -f`, `grep -rn`
- [ ] File permissions & ownership: `chmod`, `chown`, user/group/others
- [ ] Process management: `ps aux`, `top`, `kill -9`
- [ ] Networking & Remote Access: `ping`, `curl`, `ss`, SSH key authentication
- [ ] Bash Automation Mini-Project (Week 3)
