---
date: 2019-10-24 00:00:00
title: Analysis Terminology
categories:
  - Analysis
  - Malware
description:
type: Document
---

### Packed/Packer:

* Often referred to as crypted on forums
* A packer or crypter takes an executable or DLL and compresses/encrypts/obfuscates it
  * These results are then stored in another executable file, known as a Stub
  * The Stub contains the unpacking mechanism and acts as a loader for the packed file, typically performing some type of Injection

### Obfuscated/Obfuscation:

* Uses obscure text to hide commands
* Typically, used in Powershell or JavaScript to slow down analysis
* Strings in malware are sometimes obfuscated & encrypted

### Disassemblers:

* Enables understanding of file before execution
* Also known as Static Analysis
* More difficult, as you cannot view the memory
* Used to create a hypothesis as to what the malware by do before running

### Debugger:

* Follows execution of the program during run time
* Known as Dynamic Analysis
* Gives access to memory of the specific file, as well as strings, function calls, and more