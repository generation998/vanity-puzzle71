# 🔑 Puzzle 71 VanitySearch Collaboration

Help us solve the legendary **Bitcoin Puzzle #71** using distributed computing!

---

## 🎯 Target

We are searching for the private key to the following Bitcoin address:

```
1PWo3JeB9jrGwfHDNpdGK54CRas7fsVzXU
```

This is part of the well-known [Bitcoin Public Key Puzzles](https://bitcointalk.org/index.php?topic=5372024.0), specifically **Puzzle #71**.

---

## 🚀 How It Works

- The private key range is:
  ```
  0x400000000000000000 — 0x7FFFFFFFFFFFFFFFFF
  ```
- This range is split into millions of **small subranges**.
- A coordination server assigns subranges to participants.
- Each participant scans their range using `VanitySearch`.
- If a match is found, the tool stops and saves the private key.

---

## 📦 How to Join

### 1. 📥 Download the Worker Package

Download the prebuilt worker tool:  
👉 [vanity71.zip]

This includes:
- `vanity.exe` — your mining client
- No installation required

---

### 2. ▶️ Run the Worker

1. Extract the ZIP
2. Run `vanity.exe` *(double-click or via terminal)*

> The worker will automatically connect to the server, retrieve work, and begin scanning. No setup or wallet required.

---

## 🖥️ Requirements

- Windows (64-bit) or compatible with Wine
- GPU highly recommended (VanitySearch supports CUDA)
- No Python or config needed — just run the `.exe`

---

## 🙋 FAQ

**Q: Can I run this on multiple computers?**  
A: Yes! Each client will get a unique subrange. Just copy `vanity71.zip` and run it.


**Q: Can I contribute computing time anonymously?**  
A: Absolutely. No login, keys, or identity needed.

---

## ⚠️ Legal & Ethical Use

This project is a public cryptographic challenge.  
We **do not** condone using this tool to scan arbitrary wallets or addresses.

> Use this tool only as intended — for solving the Bitcoin Puzzle challenge publicly posted by the community.

---

## 🤝 Credits

- [VanitySearch by Jean-Luc Pons](https://github.com/JeanLucPons/VanitySearch)
- Coordination Server built in Python (Flask + SQLite)
- Community challenge via [bitcointalk.org](https://bitcointalk.org/index.php?topic=5372024.0)

---

## 🧠 Join the Hunt

> Every second you scan gets us closer to solving Puzzle #71.

Fire up your CPU or GPU, and let’s crack the puzzle together! 🚀
