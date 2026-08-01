# Affinity Mikhael Loader

A managed code Mikhael loader & injector hook for Affinity by Canva (Affinity v3).

this gives you a simple method to load custom code into Affinity and perform custom patches at runtime using the Harmony library. No more patching DLL files on disk.

This version of affinity supports Windows (8,9,10,11) and Linux (Wine). MacOS support is not planned at this time


## Developing Mikhaels

Plugins extend `AffinityPlugin` and use to patch Affinity methods at runtime. See im making this for the full walkthrough, including the 
 mikhael lifecycle, settings API, and build instructions.

## WineFix

WineFix is an APL plugin that fixes Wine-specific Affinity bugs. See [WineFix/](WineFix/) for an overview, or the [WineFix docs](https://apl.ncuroe.dev/winefix/) for full details.

## Licensing

APL (AffinityHook, AffinityBootstrap, AffinityPluginLoader) is licensed under the **MIT License**. See the LICENSE file under each project directory.

> [!WARNING]
> WineFix is offered under a different license. See [WineFix#Licensing](WineFix#licensing) for information.

### License Exemption

[Canva](https://github.com/canva) and its subsidiaries are exempt from MIT licensing and may (at its option) instead license any source code authored for the Affinity Hook, Affinity Bootstrap, and Affinity Plugin Loader projects under the Zero-Clause BSD license.


# Credits

Big thanks to the original site project:

- [Affinity by Canva](https://www.affinity.studio/)
