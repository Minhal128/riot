<h1 align="center" id="title">RIOT : A Worm Spreader Tool Cybersecurity Testing</h1>

<img src="https://imgur.com/ITfhVbS.jpg">

<p>RIOT (Replicate Infiltrate Obliterate Traverse) is a malicious worm program designed to replicate itself across directories and create copies of files. It can run in stealth mode and can be compiled into an executable.<p/> 


<h1 align="center" id="title">Disclaimer</h1>
<p>This is for educational purposes only. Please don't use this program for malicious activities. Misuse of this code may be illegal in some jurisdictions.</p>

<h2>🔎 Project Preview</h2>
<img src= "https://imgur.com/k26o7wd.jpg">

<h2>🧐 Features</h2>
<ul>
  <li>Replicate Worm: The worm replicates itself across directories by copying itself to multiple locations.</li>
  <li>Create File Copies: The worm makes copies of files in the scanned directories and appends its identifier to them.</li>
  <li>Stealth Mode: The worm can run stealth mode to hide the console window during execution.</li>
  <li>Compilation: The program can be compiled into a standalone executable using `g++`.</li>
  <li>Networking: The program retrieves the system's IP address to generate unique file names during replication, enhancing its ability to spread across machines in the local network.</li>
  <li>Quantum Key Distribution (QKD): Ensures secure key exchange using quantum-safe cryptographic principles, providing an additional layer of security against potential future quantum computing attacks.</li>
  <li>Base64 Encoding: Files are encoded in Base64 format for safe transmission and storage, ensuring compatibility and preventing data corruption.</li>
  <li>Encryption: All sensitive data is encrypted to maintain confidentiality and prevent unauthorized access.</li>
  
<h2>🖋 Requirements</h2>
  <ul>
    <li>Windows OS</li>
    <li>C++ Compiler (`g++` is recommended)</li>
    <li>Windows API functions (For interacting with directories, files, and system IP)</li>
    <li>Standard C++ library</li>
  </ul>

  <h2>📂 Files</h2>
  <ul>
    <li>riot.t (encrypted file if someone reliable wants to read it can take the QKD with me)</li>
    <li>public.b64.enc (public encrypted to available publically )</li>
  </ul>

  <h2>💾 Compilation</h2>
  To compile the program into an executable (`riot.exe`), run the following command:
  first, take the key with me and I will provide the QKD to decrypt it and run it as .ps1(separate methodology)

```bash
g++ -o riot.exe riot.cpp
```
<h2>💖Hope you Like my work!</h2>

This project needs a ⭐ from you. Don't forget to leave a star ⭐
