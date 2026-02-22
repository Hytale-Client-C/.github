# Hytale Client

---

## ⚠️ Legal Notice & Disclaimer

This repository does NOT contain and will NEVER contain any leaked, proprietary, or copyrighted game client files.

The original Hytale client is the intellectual property of its respective owners.
**This project does not distribute, re-host, or provide access to any leaked binaries or decompiled resources**.

Purpose of This Project

This repository exists for:

- Educational and research purposes

- Reverse-engineering practice

- Resource reconstruction and compatibility experimentation

- Technical curiosity and preservation interest

- The goal is not to enable cheating, multiplayer abuse, redistribution, or commercial use.

Important

- You must legally obtain any required binaries on your own.

- No client files are included here.

- This project does not encourage violating any game's Terms of Service.

- Any use of proprietary software is done at your own responsibility.

**If you are a rights holder and believe something here violates your rights, please open an issue for prompt review and removal.**

---

This project is an independent research effort focused on reconstructing and restoring the runtime environment required for an early C# client build.

The leaked client binaries can be decompiled with tools like dnSpy, but the executable alone is not enough to run the game. A large portion of the runtime environment depends on external assets, configuration files, shaders, UI definitions, audio mappings, and service endpoints.

This repository attempts to reconstruct those missing pieces.

## The client's work requires:

- Find the necessary dll libraries
  
- Recreated .ui markup files
  
- Shader reconstruction (VS/FS programs)
  
- Audio event mappings (Wwise compatibility)
  
- Asset atlas cache rebuilding
  
- dapt server.jar

Our main goal is to use the old client. Pure enthusiasm! There is nothing but enthusiasm. 

[Instruction manual](https://github.com/Hytale-Client-C/Guide)

