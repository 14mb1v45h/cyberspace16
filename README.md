# cyberspace16
reverse-shell powershell based 
# Dart reverse shell v1.1
Updated and (currently) working basic dart reverse shell for Windows (Powershell) based. 



# How to compile

You’ll need a platform that supports the Dart SDK. I used a Windows 10 64-bit VM for the below steps. From there:

1. Install the Dart SDK from dart.dev via the instructions (using Chocolately is easiest)

2. Grab dart.rs from this repo

3. Modify the host and port to a value that suits you

4. Open a command prompt and compile the binary with dart:


5. Transfer the binary to the target system, set up a listener on the box you configured and give it a crack:



6. OPTIONAL: Install Visual Studio Community to get ‘editbin.exe’ so you can modify your Dart shell binary to run silently. 



---

Better than it was, but could still use some improvements.

NOTE- Only for educational purpose and security research purpose 
