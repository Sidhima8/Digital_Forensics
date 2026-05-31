**Aim**
To capture a live memory dump from a system and analyze it using Volatility 3 to extract running processes, network connections, and other volatile artifacts.

**Theory**
RAM (volatile memory) contains crucial forensic artifacts that disappear when a system is powered off. Memory forensics can reveal:

Running and hidden processes
Active network connections
Encryption keys and passwords
Injected malicious code (malfind)
Loaded DLLs and kernel modules

**DumpIT**
A lightweight tool used to capture a complete RAM image from live Windows system.

**Volatility**
Open source memory analysis framework used to analyze RAM images.

**Procedure**
Download DumpIT & run it.
Identify the memory profile.
Memory image analysis.

**Conclusion**
Through this experiment, we captured the RAM contents using DumpIT and analyzed it using Volatility.
