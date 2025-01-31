# SilentXMRMiner2.0FUD
SilentXMRMiner v1.5.1 - Based on Lime Miner v0.3

Main Features

    Native & .NET - Miner installer and watchdog coded in C#, Shellcode loader/injector coded in C, miner requires .NET Framework 4.5
    Shellcode - All .NET C# parts are converted into Shellcode and injected using a native C loader, can be disabled
    Injection (Silent/Hidden) - Hide payload behind another process like explorer.exe, conhost.exe, svchost.exe or other processes
    CPU & GPU Mining - Can mine on Both CPU and GPU (Nvidia & AMD)
    Idle Mining - Can be configured to mine at different usages or not at all while computer is or isn't in use
    Stealth - Pauses the miner and clears the GPU memory while any of the programs in the "Stealth Targets" option are open
    Watchdog - Replaces the miner file if removed and starts it if the injected miner is closed down
    Remote Configuration - Can get the miner settings remotely from a URL every 100 minutes
    Bypass Windows Defender - Adds exclusions into Windows Defender for the general folders the miner uses
    Process Killer - Constantly checks for any programs in the "Kill Targets" and kills them if found
    Prebuilt FUD
