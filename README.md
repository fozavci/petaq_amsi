# Petaq AMSI Scan Buffer Bypass (Patch)

Petaq AMSI Patcher is a modified version Daniel Duggan’s AMSI Scan Buffer bypass  originally released on his Github repository (https://github.com/rasta-mouse/AmsiScanBufferBypass). <br> 
Its current version is identified by the Windows Defender’s current update level and .NET 4.8 integration. To avoid this, I obfuscated the strings, but also replaced the C# internal function Marshall.Copy with a Win API called WriteProcessMemory to the current process memory. 
