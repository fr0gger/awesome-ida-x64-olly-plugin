# Awesome IDA, Ghidra, x64DBG & OllyDBG plugins [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
A curated list of IDA x64DBG and OllyDBG plugins. [IDA](https://www.hex-rays.com/products/ida/) is a powerful disassembler and debugger that allows to analyze binary, it also includes a decompiler. [X64DBG](https://x64dbg.com/#start) is an open-source x64/x32 debugger for Windows. [OllyDbg](http://www.ollydbg.de/) is a 32-bit assembler level analysing debugger for Windows.

## Content

<!--ts-->
   * [IDA Plugins](#IDA-Plugins)
   * [Ghidra Plugins](#Ghidra-Plugins)
   * [X64dbg Plugins](#x64dbg-Plugins)
   * [OllyDBG Plugins](#OllyDBG-PLugins)
<!--te-->

## IDA Plugins

* [Keypatch](http://keystone-engine.org/keypatch): Friendly assembly-level patching/searching plugin (using multi-arch assembler framework [Keystone engine](http://keystone-engine.org) inside). 
* [Lazy ida](https://github.com/L4ys/LazyIDA): Add functionalities such as function return removing, converting data, scanning for string vulnerabilities. 
* [IDAemu](https://github.com/36hours/idaemu): Use for emulating code in IDA Pro. It is based on unicorn-engine.
* [IDA_EA](https://github.com/1111joe1111/ida_ea): A set of exploitation/reversing aids for IDA.
* [Labeless](https://github.com/a1ext/labeless): System for labels/comments synchronization with a debugger backend.
* [Idadiff](https://github.com/0x00ach/idadiff): A diffing tool using [Machoc Hash](https://github.com/ANSSI-FR/polichombr/blob/dev/docs/MACHOC_HASH.md).
* [IDA Skin](https://github.com/zyantific/IDASkins): Plugin providing advanced skinning support for IDA Pro utilizing Qt stylesheets, similar to CSS.
* [Auto Re](https://github.com/a1ext/auto_re): Auto-renaming dummy-named functions, which have one API call or jump to the imported API.
* [IDA IPython](https://github.com/james91b/ida_ipython): An IDA Pro Plugin for embedding an IPython.
* [IDA Sploiter](https://github.com/iphelix/ida-sploiter): An exploit development and vulnerability research
plugin.
* [IDATropy](https://github.com/danigargu/IDAtropy): It is designed to generate charts of entropy and histograms using the power of idapython and matplotlib.
* [IDA Patcher](https://github.com/iphelix/ida-patcher): It is designed to enhance IDA's ability to patch binary files and memory.
* [IDAHunt](https://github.com/nccgroup/idahunt): Analyze binaries with IDA Pro and hunt for things in IDA Pro.
* [IDA for Delphi](https://github.com/Coldzer0/IDA-For-Delphi): IDA Python Script to Get All function names from Event Constructor (VCL).
* [IDA ARM Highlight](https://github.com/gdelugre/ida-arm-system-highlight): Highlighting and decoding ARM system instructions.
* [BinDiff](https://www.zynamics.com/bindiff.html): It is a comparison tool for binary files, that assists vulnerability researchers and engineers to quickly find differences and similarities in disassembled code.
* [Diaphora](https://github.com/joxeankoret/diaphora): It is a program diffing plugin for IDA, similar to Zynamics Bindiff.
* [Yaco](https://github.com/DGA-MI-SSI/YaCo): Collaborative Reverse-Engineering for IDA.
* [IDASignSrch](https://sourceforge.net/projects/idasignsrch/): It can recognize tons of compression, multimedia and encryption algorithms and many other things like known strings and anti-debugging code.
* [Findcrypt2](http://www.hex-rays.com/idapro/freefiles/findcrypt.zip): It searches constants known to be associated with cryptographic algorithm in the code.
* [Driver Buddy](https://github.com/nccgroup/DriverBuddy): It assists with the reverse engineering of Windows kernel drivers.
* [Heap Viewer](https://github.com/danigargu/heap-viewer): Used to examine the glibc heap, focused on exploit development.
* [IDAScope](https://bitbucket.org/daniel_plohmann/simplifire.idascope):  It consists of multiple tabs, containing functionality to achieve different goals such as fast identification of semantically interesting locations.
* [HexRayPytools](https://github.com/igogo-x86/HexRaysPyTools): Assist in the creation of classes/structures and detection of virtual tables. 
* [Ponce](https://github.com/illera88/Ponce): Symbolic Execution just one-click away!
* [idenLib.py](https://github.com/secrary/IDA-scripts/tree/master/idenLib): [idenLib](https://github.com/secrary/idenLib) (Library Function Identification ) plugin for `IDA Pro`
* [J.A.R.V.I.S](https://github.com/carlosgprado/JARVIS) A plugin for IDA Pro to assist you with the most common reversing tasks. It integrates with the (J.A.R.V.I.S) tracer.
* [golang_loader_assist](https://github.com/strazzere/golang_loader_assist): Making GO reversing easier in IDA Pro
* [FindYara](https://github.com/OALabs/FindYara): IDA python plugin to scan binary with yara rules.
* [Karta](https://github.com/CheckPointSW/Karta): Source code assisted fast binary matching plugin for IDA
* [VT-IDA-PLUGIN](https://github.com/VirusTotal/vt-ida-plugin): This plugin integrates functionality from VirusTotal web services into the IDA Pro's user interface.
* [mkYARA](https://github.com/fox-it/mkYARA): mkYARA comes with a IDA plugin to easily create YARA signatures by selecting a set of instructions and choosing one of the mkYARA -> Generate YARA rule options.
* [Oregami](https://github.com/shemesh999/oregami): IDA plugins and scripts for analyzing register usage frame.
* [IDA_IFL](https://github.com/hasherezade/ida_ifl): A small plugin with a goal to provide user-friendly way to navigate between functions and their references.
* [xray](https://github.com/patois/xray): xray is a plugin for the Hexrays decompiler that both filters and colorizes the textual representation of the decompiler's output based on configurable regular expressions.
* [Lighthouse](https://github.com/gaasedelen/lighthouse): Lighthouse is a powerful code coverage plugin for IDA Pro and Binary Ninja. As an extension of the leading disassemblers, this plugin enables one to interactively explore code coverage data in new and innovative ways when symbols or source may not be available for a given binary.
* [CAPA Explorer](https://github.com/fireeye/capa/tree/master/capa/ida/plugin): Capa explorer is an IDA Pro plugin written in Python that integrates the FLARE team's open-source framework, capa, with IDA.
* [Ghida](https://github.com/Cisco-Talos/GhIDA): GhIDA is an IDA Pro plugin that integrates the Ghidra decompiler in IDA.
* [vt-ida-plugin](https://github.com/VirusTotal/vt-ida-plugin): This plugin integrates functionality from VirusTotal web services into the IDA Pro's user interface.
* [Virtuailor](https://github.com/0xgalz/Virtuailor): IDAPython tool for C++ vtables reconstruction.
* [ipyda](https://github.com/eset/ipyida): PyIDA is a python-only solution to add an IPython console to IDA Pro.
* [ComIDA](https://github.com/airbus-cert/comida): An IDA Plugin that help during the analysis of modules using COM.
* [D810](https://gitlab.com/eshard/d810): D-810 is an IDA Pro plugin which can be used to deobfuscate code at decompilation time by modifying IDA Pro microcode.
* [lumen](https://github.com/naim94a/lumen): A private Lumina server for IDA Pro.
* [Hexrays Toolbox](https://github.com/patois/HexraysToolbox): Hexrays Toolbox is a script for the Hexrays Decompiler which can be used to find code patterns within decompiled code.
* [HRDevHelper](https://github.com/patois/HRDevHelper): This plugin for the HexRays decompiler creates a graph of a decompiled function's AST using IDA's internal graph viewer. 
* [ida-minsc](https://github.com/arizvisa/ida-minsc): IDA-minsc is a plugin for IDA Pro that assists a user with scripting the IDAPython plugin that is bundled with the disassembler. 

## Ghidra Plugins
* [Ghidra Scripts](https://github.com/tacnetsol/ghidra_scripts): Port of devttyS0's IDA plugins to the Ghidra plugin framework, new plugins as well.
* [Ghidra Scripts 2](https://github.com/AllsafeCyberSecurity/ghidra_scripts): Ghidra script for malware analysis. 
* [Findcrypt](https://github.com/d3v1l401/FindCrypt-Ghidra): IDA Pro's FindCrypt ported to Ghidra, with an updated and customizable signature database.
* [Lazy Ghidra](https://github.com/AllsafeCyberSecurity/LazyGhidra): Make your Ghidra Lazy.
* [Pcode Emulator](https://github.com/kc0bfv/pcode-emulator): A PCode Emulator for Ghidra.

## x64dbg Plugins
* [Checksec](https://github.com/klks/checksec): x64dbg plugin to check security settings.
* [ClawSearch](https://github.com/codecat/ClawSearch): A memory scanner plugin for x64dbg, inspired by Cheat Engine.
* [x64DBGPYLIB](https://github.com/x64dbg/x64dbgpylib): Port of windbglib to x64dbgpy, in an effort to support mona.py in x64dbg.
* [xAnalyzer](https://github.com/ThunderCls/xAnalyzer): It is capable of doing various types of analysis over the static code of the debugged application to give more extra information to the user. 
* [x64DBGIDA](https://github.com/x64dbg/x64dbgida): Official x64dbg plugin for IDA Pro.
* [x64dbg Dark Theme](https://github.com/nextco/x64dbg-dark): Simple dark theme. 
* [X64DBG YaraGen](https://github.com/mrexodia/YaraGen): Generate Yara rules from function basic blocks.
* [Diff](https://github.com/mrexodia/Diff): Very simple plugin to diff a section in memory with a file.
* [Unpacking Script](https://github.com/x64dbg/Scripts): Unpacking script for x64dbg.
* [Anti Anti](https://github.com/brock7/xdbg): Open-source user-mode Anti-Anti-Debug plugin.
* [ScyllaHide](https://github.com/x64dbg/ScyllaHide): https://github.com/x64dbg/ScyllaHide
* [Highlightfish](https://github.com/Insid3CodeTeam/Highlightfish): Plugin to customize x64dbg.
* [TitanHide](https://github.com/mrexodia/TitanHide): It is a driver intended to hide debuggers from certain processes.
* [idenLibX](https://github.com/secrary/idenLibX): [idenLib](https://github.com/secrary/idenLib) (Library Function Identification ) plugin for `x32dbg`/`x64dbg`
* [Official x64dbg plugins](https://github.com/x64dbg/x64dbg/wiki/Plugins): Official repository of the x64dbg debugger plugins. 

## OllyDBG Plugins
* [OllyDumpEx](https://tuts4you.com/download/3451/): This plugin is process memory dumper for OllyDbg.
* [OllyDeobfuscator](https://tuts4you.com/download/3549/): Deobfuscator for Olly.
* [Phantom](https://tuts4you.com/download/1276/): Anti anti-debug trick.
* [TLSCatch 0.3](https://tuts4you.com/download/3014/): This plugin simply intercepts any new module loaded into the current process address space, searches it for TLS callbacks.
* [AnalyzeThis](https://tuts4you.com/download/2848/): Assisting for unpacking. 
